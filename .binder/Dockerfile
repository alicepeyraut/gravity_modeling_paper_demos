
FROM ghcr.io/alicepeyraut/gravity_modeling_paper_demos_github:9ef7577b83bd32d76b793d10f15fc34564c97904:latest

ARG NB_USER=jovyan
ARG NB_UID=1000
USER ${NB_USER}
ENV HOME /home/${NB_USER}
COPY --chown=${NB_UID} . ${HOME}
