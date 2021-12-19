FROM registry.fedoraproject.org/fedora-toolbox:35

COPY extra-packages /
RUN dnf -y install $(<extra-packages) && rm /extra-packages

