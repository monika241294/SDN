# SDN
#Flow Clustering (unsupervised learning) and Classification (supervised learning) for Load-Balanced SDN Controller Operation 
   
   In recent days internet is busy with huge traffic. With the landing of new inventions generally in the ranges of mobile, social, and big datacenters, computer networks require high data transfer capacity, and effective management.
 
  In 2008 analyst at Sanford University proposed a revolutionized idea knowns as software Defined Networking (SDN) in order to enhance the versatility, and ability of network. SDN center thought is to isolate the control plane from forwarding plane, what’s more control plane is programmable specifically. This SDN invention proposing the idea of isolation and transmitting load balancing.The forwarding plane and the control plane are isolated. For correspondence among control and forwarding plane open flow protocol is utilized.
 
  There are three main layers of SDN architecture such as 1) Application layer, 2) Infrastructure layer, and 3) Control layer. With the some advantage of SDN advantages, there are some SDN research challenges. Quality of Service (QoS), load balancing, security, and scalability are SDN research challenges.
  
  To serves huge number of request per day different servers ought to be utilized as single asset and every request ought to be re-enacted as various servers. To disperse all request to multiple servers load balancing procedure is utilized. There are diverse load balancing technique to disseminate circulate the burden to various devices.
  
  In SDN load balancing implied a productive and clever blockage mindful directing resolution. In the light of SDN condition it is a fundamental limitation to enhance the adaptability and accessibility of network which prompts accomplish greatest number of packets dealt with by the controller in insignificant time for any application.
  
  With the SDN controller the load balancing design comprises of open flow switch in which various servers are associated with it. SDN controller keeps p rundown of live servers that are associated with the open flow switch, and every server is appointed with static IP address. On an outstanding port 80 web facility is running on every server, virtual address covers by controller and to the virtual IP address all requests from the customers are sent. When the customers sends a request to the virtual IP, open flow switch utilized the data contained in bundle header and contrast it and flow passages in switch and if the customers bundle header data coordinates with flow section, at that point switch alter the goal virtual IP deliver to the address of one of the servers in view of load balancing procedure and forward the request to that server.

  we proposed a multi controller load balancingapproach for SDN called ClusterFlow (DCF). This method simpliﬁes the load balancing operation and breaks the dependency between the SC and RCs during the periodicalload balancing.

https://youtu.be/vR1FS58ZPA8 youtube video
