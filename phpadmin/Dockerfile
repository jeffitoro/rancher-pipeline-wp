FROM phpmyadmin/phpmyadmin

COPY lizhi-phpadmin.txt    /var

EXPOSE 80

ENTRYPOINT [ "/run.sh" ]

CMD ["supervisord", "-n", "-j", "/supervisord.pid"]

