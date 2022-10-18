# GEOSfvdycore Dockerfile

ARG osversion
ARG imagename
ARG baselibversion
ARG mpiname
ARG mpiversion
ARG compilername
ARG compilerversion

ARG BASE_IMAGE=gmao/${osversion}-${imagename}:${baselibversion}-${mpiname}_${mpiversion}-${compilername}_${compilerversion}
FROM ${BASE_IMAGE}

ARG fv3version

RUN git clone -b ${fv3version} https://github.com/GEOS-ESM/GEOSfvdycore.git /GEOSfvdycore-src && \
    cd /GEOSfvdycore-src && \
    mepo clone && \
    mkdir build && \
    cd build && \
    cmake .. -DCMAKE_INSTALL_PREFIX=/GEOSfvdycore/install -DBASEDIR=$BASEDIR/Linux -DUSE_F2PY=OFF -DCMAKE_Fortran_COMPILER=$FC -DCMAKE_C_COMPILER=$CC -DCMAKE_CXX_COMPILER=$CXX && \
    make -j $(nproc) install/strip && \
    cd / && \
    rm -rf /GEOSfvdycore-src
