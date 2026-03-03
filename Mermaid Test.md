

Test


[[Note in Folder test]]


```mermaid  
flowchart TD  
A[Dell WD19 Docking Station] --> B{Is it plugged in?}  
B -->|Yes| C[Are Display or HDMI Cables properly seated]  
B -->|No| D[Plug Dock Into Power]
```



```mermaid
flowchart TD
A[Dell WD19 Docking Station]
A --> B{Is it plugged in?}
B -->|Yes| C[Check Display Output]
B -->|No| D[Plug Dock Into Power]
```


``` mermaid
flowchart TD
A[Dell WD19 Docking Station] --> B{Is it plugged in?}

B -->|No| C[Plug Dock Into Power]

B -->|Yes| D{Are monitors detected?}

D -->|Yes| E[Issue Resolved]

D -->|No| F{Are drivers installed?}

F -->|Yes| G[Update Firmware]

F -->|No| H[Install Drivers]
```


``` mermaid
%%{init: {"securityLevel":"loose"}}%%
flowchart TD

A(Dell WD19 Docking Station)
A --> B(Is it plugged in?)

B -->|Yes| C(Are Display/HDMI Cables Seated?)
B -->|No| D(Plug Dock Into Power)

C -->|Yes| E(Can Device Manager see Displays?)
C -->|No| F(Seat them properly)

E -->|No| G(Additional note test)

click G "README.md"

```
