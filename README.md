# hackathon-family-tree
Tracing the lineage of the EU hackathon scene! 


![Mermaid render](https://cloud.githubusercontent.com/assets/1790822/22555825/5ed6cf6e-e965-11e6-99ac-87fdb12378a3.png)



If you think you know where a hackathon lives in this tree, or you see an error, please create a pull request. 

Whilst we go through data discovery, this will initially be an awful list of lists. There may be repeated data as nested lists don't express multiple-parents very well. 

Below is the starting of a [Mermaid](https://knsv.github.io/mermaid/) graph.

# The Yahoo! Hack Dynasty

- Yahoo! Hack
  - Over The Air
  - CharityHack (also parented by BarCamp)
    - BattleHack
  - LeedsHack
    - HackManchester
      - Hack24
        - LincolnHack
        - HackTheMidlands
  - Hacked.io (also parented by Mashed 2008)
    - Hackference (also parented by Kings of Code)
      - BanterHack
      - BrumHack (The Jack and Lily Generation)
      - HackNotts
        - AnvilHack
          - Sex Tech Hack
        - Launch Hack (also parented by StudentHack)
          - DragonHacks
          - HackNE
          - Landing Hack
          - WarwickHACK
            - CUCC Hack
          - Hack the Holidays
          - Hack the Burgh
          - StacsHack
            - StirHack
            - StrathHack
            - HackDee
            - RGU Hack

# PennApps Dynasty

- PennApps
  - KairosHacks
    - HackUPC
  - HackCambridge
  - AGHacks (also parented by MHacks)
  
# House of the Civic Hackathons 
### (Otherwise known as "Kevin's Fault")

- National Hack the Government
  - Young Rewired State
    - BrumHack (Poppie)
      - Aston Hack 
      - HackTheMidlands (also parented by Hack24)
      - HackBordeaux
    - RU Hacking
  - Parly Hack
      - Accountability Hack
  - UKGovHack
 
# Fallen Angels

- AngelHack
  - jacobsHack!
    - CopenHacks
    - LauzHack
      - OpenFood Hackdays
    - OxfordHack
    - DO!Hack
    - StudentHack
      - Launch Hack
      - GreatUniHack

# Orphaned Houses

- HackKings
  - HackLondon
    - Porticode (also parented by NYC Unhackathon)
    - HackCity
  - HackCortona
- ICHack
- JP Morgan Code For Good
  - DurHack
- HackaSoton
    - HackTrain
- StartHack
- HackZurich
    
# Mermaid Graph
[View the graph](http://bit.ly/hheutree)  
[Edit the graph](http://bit.ly/hheutreeedit)

graph TD;  
    Yahoo!Hack-->CharityHack;  
    Yahoo!Hack-->LeedsHack;  
    Yahoo!Hack-->Hacked.io;  
    Yahoo!Hack-->OverTheAir;  
    Mashed2008-->Hacked.io;  
    CharityHack-->BattleHack;  
    Hacked.io-->Hackference;  
    KingsOfCode-->Hackference  
    LeedsHack-->HackManchester;  
    HackManchester-->Hack24;  
    Hack24-->LincolnHack;  
    Hack24-->HackTheMidlands;  
    Hackference-->BanterHack;  
    Hackference-->BrumHack;  
    Hackference-->HackNotts;  
    HackNotts-->AnvilHack;  
    AnvilHack-->SexTechHack;  
    HackNotts-->LaunchHack;  
    StudentHack-->LaunchHack;  
    LaunchHack-->DragonHacks;  
    LaunchHack-->HackNE;  
    LaunchHack-->LandingHack;  
    LaunchHack-->WarwickHACK;  
    WarwickHACK-->CUCCHack;  
    LaunchHack-->HackTheHolidays;  
    LaunchHack-->HackTheBurgh;  
    LaunchHack-->StacsHack;  
    StacsHack-->StirHack;  
    StacsHack-->StrathHack;  
    StacsHack-->HackDee;  
    StacsHack-->RGUHack;  
    PennApps-->KairosHacks;  
    KairosHacks-->HackUPC;  
    PennApps-->HackCambridge;  
    PennApps-->AGHacks;  
    MHacks-->AGHacks;  
    NationalHackTheGovernment-->YoungRewiredState;  
    YoungRewiredState-->BrumHack;  
    YoungRewiredState-->RUHacking;    
    BrumHack-->AstonHack;  
    BrumHack-->HackTheMidlands;  
    BrumHack-->HackBordeaux;
    NationalHackTheGovernment-->ParlyHack;  
    NationalHackTheGovernment-->UKGovHack;  
    AngelHack-->jacobsHack!;  
    AngelHack-->StudentHack;
    jacobsHack!-->CopenHacks;  
    jacobsHack!-->LauzHack;  
    LauzHack-->OpenFoodHackdays;
    jacobsHack!-->OxfordHack;  
    jacobsHack!-->DO!Hack;  
    StudentHack-->GreatUniHack;  
    HackKings-->HackLondon;  
    HackKings-->HackCortona;  
    HackLondon-->Porticode;  
    HackLondon-->HackCity;  
    ICHack;
    StartHack;
    HackZurich;
    JPMCodeForGood-->DurHack;  
    HackaSoton-->HackTrain;  
    HackSheffield;
    CUCCHack-->CovHack;
    
