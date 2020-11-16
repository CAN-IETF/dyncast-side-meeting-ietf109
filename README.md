# CFN-dyncast (Dyncast in CFN) Virtual Side meeting in IETF 109

## Time: Wed (Nov 18) , 75min, 5 min after plenary ends
  - UTC 10:45 - 12:00
  - CET (UTC+1) 11:45 - 13:00
  - Bangkok Time (UTC+7) 17:45 - 19:00
  - CST (UTC+8) 18:45 - 20:00
  - PST (UTC-8) 02:45 - 04:00

Information also available on side meeting wiki: https://trac.ietf.org/trac/ietf/meeting/wiki/109sidemeetings

## Webex
- Webex Meeting number (access code): 175 335 6387 
- Password:7wrDVwRt7B4
- Password if joining from a phone: 79738978
- Webex: https://fipe-meeting.my.webex.com/fipe-meeting.my/j.php?MTID=m2e7d90ec32145ba12f4a6b7e8baf3bcd


## Drafts:
- draft-geng-rtgwg-cfn-dyncast-ps-usecase
- draft-li-rtgwg-cfn-dyncast-architecture 


## Purpose of the virtual side meeting:
- Understand the use cases, problem space, gaps and challenges
- Review the framework, is it a right direction to go? 
- Discuss the potential work and where to fit them in IETF?

## Introduction
Service providers are exploring the edge computing to achieve better response time and control over data by moving the computing services towards the edge of the network. 
There could be a huge number of edge sites, and at the same time each edge site has a limited and very dynamic computing capacity and load characteristics. 

Then the problem comes as how to optimally route service demands based on computing and network metrics to the best edge. 

Most current practices uses random or round robin way or use geographically closest one to decide the edge to handle the service demand. It considers the static characteristics like aliveness and geographical distance of edges. Dynamic status like computing load and network path status are not taken into account. In addition, the practices usually determine the best edge in respect to the computing and networking aspects separately rather than jointly.  

CFN-Dyncast (dynamic ancyast) tries to route the computing service demands based on computing and network metrics at the same time at the network layer. Three features are identified to be supported:
* Anycast based service addressing methodology 
* Flow affinity
* Computing Aware Routing

CNF-Dyncast could focus on:
* Specification of CFN dyncast framework and functional components 
* Reuse existing IETF protocols when possible. Define protocol extensions when needed or introduce a new protocol when necessary including features like:
  - Represent computing metrics in defined service/service instance context 
  - Distribute the metrics, format and how dynamic/frequent the updates should be
  - Use the metrics in route determination
  - Definition of requirements for any new data plane extensions and procedures.

Comments and suggestions are welcome. 



