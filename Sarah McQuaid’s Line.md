```mermaid
flowchart TD

%% Colors %%

classDef red fill:#8B0000,stroke:#000,color:#FFF
classDef gold fill:#FFCC33,stroke:#FFF,color:#FFF

%% Sarah McQuaid's Line %%
M209("Sarah McQuaid"):::gold
M209-----M258
M209------M288
M258("Nicholas Garcia"):::red
M258---M285
M285("Priscila Romo"):::red
M285---M306
M288("Emma Rader"):::red
M288---M305
M305("Deva Issa"):::red
M306("Camryn Wagner"):::red

%% Co-Relationships & Current Pledges %%
M261("Kayla Waswil")
M261----M305
```