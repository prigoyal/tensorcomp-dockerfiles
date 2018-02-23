ARG BUILD_ID
FROM registry.pytorch.org/tensorcomp/linux-xenial-gcc5:${BUILD_ID}

ARG BUILD
ADD ./common/install_cuda.sh install_cuda.sh
RUN bash ./install_cuda.sh

CMD ["bash"]
