FROM mcr.microsoft.com/dotnet/sdk:5.0

LABEL org.opencontainers.image.source https://github.com/getgatekeeper/ldapserverlibrary

RUN apt-get update
RUN apt-get install -y ldap-utils netcat lsof zsh tcpdump vim
RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "" --unattended
