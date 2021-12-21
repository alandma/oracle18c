FROM alandma/oracle18c:18.4.0-xe

COPY --chown=oracle:oinstall ./dump/ /opt/oracle/dpdump

COPY --chown=oracle:dba ./scripts/ /opt/oracle/scripts/setup
