# helm-matrix

This helm chart will deploy the 3 base components:
 - synapse 
 - coturn
 - ma1sd (the identity server)

## Usage
Due to the way the docker image are made most of the configuration has still to be done in the config files.
Those are located on the persistents volumes, once changed just delete the pods to restart the service.
