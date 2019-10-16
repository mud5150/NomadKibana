# NomadKibana
Kibana image with opendistro plugins installed to run on Nomad cluster

TODO: Build time optimize still not working correctly causing slow startup. Will need to investigate this further when I have time. For now increasing `healthy_deadline` in Nomad job. 