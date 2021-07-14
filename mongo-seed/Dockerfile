FROM mongo

COPY dealershipreadmodel.json /dealershipreadmodel.json
#COPY closestatusresponsereadmodel.json /closestatusresponsereadmodel.json
CMD mongoimport --host mongodb --db ukplatform-local-readstore --collection DealershipReadModel --type json --file /dealershipreadmodel.json --jsonArray \
    # && mongoimport --host mongodb --db ukplatform-local-readstore --collection CloseStatusResponseReadModel --type json --file /closestatusresponsereadmodel.json --jsonArray
    # example for later use, will need valid data