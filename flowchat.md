graph TD
    A[Citizen finds illegal dumping area] --> B(Upload photo to AI Assistant)
    B --> C{IBM Granite 3.2 Vision}
    C -->|Identify Waste & Size| D
    D -->|Policy Reasoning| E{IBM Granite 3.2 Instruct}
    E -->|Automated Draft| F
    F --> G(Clean-up & Cleaner Air Impact)
    
    style C fill:#f9f,stroke:#333,stroke-width:2px
    style E fill:#bbf,stroke:#333
