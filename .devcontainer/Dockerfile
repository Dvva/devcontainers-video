FROM  mcr.microsoft.com/devcpmyaomers/universal:2-linux

RUN mkdir /newdir   \ 
    && touch /newdir/newfile.txt

RUN echo "https://mirror.tuna.tsinghua.edu.cn/alpine/v3.4/main" > /etc/apk/repositories \
    && echo "https://mirror.tuna.tsinghua.edu.cn/alpine/v3.4/community" >> /etc/apk/repositories \
    && echo "https://mirror.tuna.tsinghua.edu.cn/alpine/edge/testing" >> /etc/apk/repositories  \
    && git config --global url."https://mirror.ghproxy.com/https://github.com/".insteadOf "https://github.com/"



