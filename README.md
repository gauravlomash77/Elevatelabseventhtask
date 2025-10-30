# ElevateLab Task 7 — Monitor System Resources Using Netdata

##  Objective
Install **Netdata** using Docker to visualize system and application performance metrics in real-time.

---

##  Tools Used
- **Netdata** — Free, open-source monitoring tool for real-time system metrics.
- **Docker** — Used to containerize and run Netdata easily.

---
## Steps Performed

### Pull and Run Netdata Docker Container
docker pull netdata/netdata
docker ps
docker logs netdata | head
![Netdata Imagepull Screenshot](/screenshots/Netdata-image-pull.png)
![Netdata container Screenshot](/screenshots/Netdat-Conatiner-logs.png)

### Netdata Running
ss -tulnp | grep 19999
![Netdata Running](/screenshots/Netdata-running.png)

### Access the Netdata Dashboard
![Netdata Dasboard](/screenshots/Netdata-dashboard.png)

### Memory panel
![Netdata Dasboard](/screenshots/Memory-panel.png)

## Outcome

By completing this task, you have:

-  Successfully **deployed and run Netdata using Docker**.  
-  Learned how to **visualize CPU, memory, disk, and network metrics** in real-time.  
-  Understood how **Netdata provides lightweight monitoring** for servers and applications.  
-  Explored **alerts, logs, and performance charts** for proactive system monitoring.  

**Final Understanding:**  
Netdata offers an easy, efficient, and powerful way to track real-time resource usage and performance metrics without heavy setup. It’s ideal for developers and DevOps engineers who need quick visibility into system health.
