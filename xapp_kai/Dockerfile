FROM emoro/xapp:latest

RUN echo "sleep 60 && python3 myxapp.py 1>&2" > "./run_xapp.sh"
RUN chmod +x "./run_xapp.sh"
ENTRYPOINT [ "/bin/sh" ]
CMD [ "./run_xapp.sh" ]