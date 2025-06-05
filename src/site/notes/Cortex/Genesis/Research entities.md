---
{"dg-publish":true,"dg-path":"Genesis/Research entities.md","permalink":"/genesis/research-entities/"}
---


## **[[Waypoint/Domains/The Foundation/The Foundation\|The Foundation]]** 
This the umbrella organization for funding and that will incorporate:

- [[Waypoint/Domains/The Foundation/Ministry of Research and Education/Academic & Research Council/Research INDEX API\|Research INDEX API]]: (Integrated Database for Established Research) can serve as a comprehensive knowledge and publication aggregator, providing structured access to research papers, books, journals, reports, and other academic or non-academic written works.
- [[Waypoint/Domains/The Foundation/Digital & Technological Innovation/Citizen ID\|Citizen ID]]: ID Database, integrated for authentication.
- [[Waypoint/Domains/The Foundation/Ministry of Research and Education/Academic & Research Council/The Encyclopedia\|The Encyclopedia]]: A real-time, continuously updated encyclopedia that acts as a living, GitHub-like repository of Knowledge Encyclopedia.
-  **Open Challenges Archive**: Free, public repository of problems and simulations
- **Open Education Standards**: Course metadata schema, learning progress interoperability, API specs  
## The Research and Education Division of House
### [[Waypoint/Domains/House of El Han/Ministry of Education & Research/GNOSIS, Inc/GNOSIS, Inc\|GNOSIS, Inc]]
- **[[Eκμάδεση/Projects & Research/Projects & Contributions/Scholarly.org\|Scholarly.org]]:** The central client app for Research INDEX—a dynamic, interactive, and universally accessible repository for research.
	- User libraries, connected notes, ai chats and so on.
	- [[scholarly ID\|scholarly ID]] :  Scholarly and User Management and Authentication Backend.
	- [[Cortex/Genesis/Scholarly City\|Scholarly City]]: A potential social network or collaborative space that connects folks, discussion, and facilitates data sharing.
		- Forums, Private communities 
	- [[Cortex/Genesis/Scholarly IDE\|Scholarly IDE]]: The Ultimate One
		- Cross-platform
		- Local-first, file based 
		- Personal and Group Servers > Multiple Vaults
	- [[Scholarly Cloud IDE\|Scholarly Cloud IDE]]
		- Storage
		- Co-lab on specific files or directories 
	- [[Scholarly Maps\|Scholarly Maps]]
	- [[Eκμάδεση/Projects & Research/Projects & Contributions/scholarly omics\|scholarly omics]]
	- [[Eκμάδεση/Projects & Research/Projects & Contributions/scholarly linguistics\|scholarly linguistics]]
	- [[Eκμάδεση/Projects & Research/Projects & Contributions/Scholarly ilm\|Scholarly ilm]]
	- [[Scholarly physics\|Scholarly physics]]
- [[Waypoint/Domains/House of El Han/Ministry of Education & Research/GNOSIS, Inc/Biosis/Biosis\|Biosis]]: A cloud-native software suite that empowers scientists, engineers, and creators to design, simulate, and build living systems—from DNA sequences to full synthetic organisms.
- [[Waypoint/Domains/House of El Han/Ministry of Technology & Engineering/Han's Labs/Physis\|Physis]]

### [[Waypoint/Domains/House of El Han/Ministry of Education & Research/COMET/COMET\|COMET]]
A Federated Online Study Platform Student management and learning managemenet app build on the protocols of  The Foundation
- [[Alpenglow\|Alpenglow]]

### **[[Waypoint/Domains/House of El Han/Ministry of Education & Research/CORDE/CORDE\|CORDE]]** 
This a separate entity representing the research institutions. These institutions can publish independently, but may also interface with the Foundation’s components.
- [[Waypoint/Domains/House of El Han/Ministry of Education & Research/CORDE/Alanoma Research/Alanoma Research\|Alanoma Research]]
- [[Waypoint/Domains/House of El Han/Ministry of Education & Research/CORDE/Elixir Research\|Elixir Research]]
- [[Waypoint/Domains/House of El Han/Ministry of Education & Research/CORDE/Allele Research\|Allele Research]]

### [[Waypoint/Domains/House of El Han/Ministry of Education & Research/Times of Titans/Times of Titans\|Times of Titans]]


## **Publications & Dissemination** 
It can either be integrated with Foundation or managed separately. They represent the diverse channels where research outputs are published, archived, and disseminated repositories, depending on the structure of ecosystem. Future thingy.
- [[Waypoint/Domains/House of El Han/Ministry of Arts and Culture/The Publishing House/The Publishing House\|The Publishing House]]
	- 


---


```mermaid
graph LR

  subgraph House ["House"]
    GNOSIS["GNOSIS"]
    COMET["COMET"]
    CORDE["CORDE"]
    TITANS["TITANS"]
  end

  subgraph GNOSIS_Sub ["GNOSIS Components"]
    Scholarly_org["Scholarly.org"]
    Scholarly_ID["Scholarly ID"]
    Scholarly_City["Scholarly City"]
    Scholarly_IDE["Scholarly IDE"]
    Scholarly_Cloud_IDE["Scholarly Cloud IDE"]
    Scholarly_Maps["Scholarly Maps"]
    Scholarly_Omics["Scholarly Omics"]
    Scholarly_Physics["Scholarly Physics"]
    SimCity["Sim City"]
    Biosis["Biosis"]
    Physis["Physis"]
  end

  subgraph CORDE_Sub ["CORDE Entities"]
    Alanoma["Alanoma Research"]
    Sentinel["Sentinel Research"]
    Watchtower["Watchtower"]
  end

  subgraph COMET_Sub ["COMET Components"]
    LearningPlatform["Online Learning Interface"]
    LearnerID["Student Identity & Records"]
  end

  subgraph TITANS_Sub ["TITANS Ecosystem"]
    Arena["Cognitive Arena"]
    Tournaments["Discipline-Based Olympiads"]
    SchoolCompetitions["School Competitions"]
  end

  %% GNOSIS children
  GNOSIS --> Scholarly_org
  GNOSIS --> SimCity
  Scholarly_org --> Scholarly_ID
  Scholarly_org --> Scholarly_City
  Scholarly_org --> Scholarly_IDE
  Scholarly_org --> Scholarly_Cloud_IDE
  Scholarly_org --> Scholarly_Maps
  Scholarly_org --> Scholarly_Omics
  Scholarly_org --> Scholarly_Physics
  SimCity --> Biosis
  SimCity --> Physis

  %% CORDE children
  CORDE --> Alanoma
  CORDE --> Sentinel
  CORDE --> Watchtower

  %% COMET children
  COMET --> LearningPlatform
  COMET --> LearnerID
  
  %% TITANS children
  TITANS --> Arena
  TITANS --> Tournaments
  TITANS --> SchoolCompetitions
```

```mermaid
graph LR
  subgraph Foundation ["The Foundation"]
    INDEX_API["INDEX API<br>Research publication aggregator"]
    Citizen_ID["Citizen ID"]
    Encyclopedia["Encyclopedia for Integrated Knowledge"]
    Open_Challenges["Challenges Archive"]
    Open_Edu_Standards["Education Standards Protocols"]
  end
```
