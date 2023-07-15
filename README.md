# Kubernetes Cluster Monitoring  

The project aims to monitor Kubernetes clusters in any service using Prometheus and Grafana.   
The data is scrapped from Kubernetes API server in regular intervals of time and stored in Prometheus.  
The data is then exported to Grafana to gain complex metrics in visually appealing graphs or charts.  

Major steps to follow:   
1.) Create the required namespace, role, configMap and deployment in Kubernetes using YAML config files.     
2.) Expose the prometheus deployment to appropriate port and start collecting data from the cluster.   
3.) Expose the grafana deployment to appropriate port and display the data in the form of charts and graphs.
