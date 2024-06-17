version: 1
task_description: 'Teach the model condtitions on which renewable energy sources can be build in a given area'
created_by: michalkordyzon
domain: local development plans
seed_examples:
 - question: Is it allowed to build renewable energy sources or devices in Warsaw, Białołęka district on Kobiałka Street?
   answer: |
     Yes renewable energy sources are allowed to build, but only solar energy or geothermal energy, with a power not exceeding the power of the micro-installation.
- question: Is wind energy allowed in Warsaw, Białołęka district on Kobiałka Street?
   answer: |
     No, wind energy is not allowed, only solar energy or geothermal energy can be build in this area accoring to local development plans from local municipal office.
 - question: What conditions do I need to meet to use or build renewable energy sources in Warsaw, Białołęka district on Kobiałka Street? 
   answer: |
     There are following conditions for using renewable energy sources or devices on Kobiałka Street, Białołęka district, Warsaw: they cannot exceed the power of the micro-installation(including hybrid installation), they may be used for enrgy production or heating purposes.
 - question: May I build renewable energy devices in Warsaw, Wilanów district on Vogla Street?
   answer: |
     Yes you can build renewable energy devices on Voglda Street, Wilanów, Warsaw, including those burning fuels that are the least harmful to the environment, provided that the maximum total height of the devices cannot be higher than 15 meters from the ground level. 
 - question: What are conditions for building renewable energy sources in Warsaw, Wilanów district on Vogla Street? 
   answer: |
     The conditions for building and using renewable energy sources or devices on Vogla Street are: you can use devices burning fuels that are the least harmful to the environment, you can build any devices provided that the maximum total height of the devices cannot be higher than 15 meters from the ground level.
- question: Is wind energy allowed in Warsaw, Wilanów district on Vogla Street?
   answer: |
     Yes, wind energy is allowed, on condition that device is not higher than 15 meters from the ground level
 - question: Is it allowed to build renewable energy sources or devices in Warsaw, Włochy district on Ryzowa Street?
   answer: |
     Yes, it is agreed that individual energy sources will use cogeneration or renewable devices energy sources using only solar, wind or geothermal energy with a power not exceeding 500 kW for free-standing devices.
 - question: Give me conditions for building renewable energy devices in Warsaw, Włochy district on Ryzowa Street.
   answer: |
     The conditions for building renewable energy sources in this area are: only solar, wind or geothermal energy is allowed. The power for those devices cannot exceed 500 kW for free-standing devices.
- question: Is wind energy allowed in Warsaw, Włochy district on Rozowa Street?
   answer: |
     Yes, wind energy is allowed in this area.
document:
 repo: https://github.com/juliadenham/oscars2024_knowledge.git
 commit: e1744af
 patterns:
   - local_dev_plans.md
