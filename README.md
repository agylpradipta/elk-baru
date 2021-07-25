Cara menjalankan:
1. kubectl apply -f persistance-volume.yaml
2. kubectl apply -f elk-state.yaml
3. kubectl apply -f kibana.yaml
4. kubectl apply -f ingress-elk.yaml
5. cd filebeat
6. kubectl apply -f filebeat-kubernetes.yaml  
7. kubectl apply -f metricbeat-kubernetes.yaml
