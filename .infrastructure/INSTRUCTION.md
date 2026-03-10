To deploy daemonset.yml and cronjob.yml use commands:

    cd ./.infrastructure
    
    kubectl apply -f daemonset.yml

    kubectl apply -f cronjob.yml

To watch logs use command:

    kubectl logs <daemonset_name>

    kubectl logs <cronjob_name>
