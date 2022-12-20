```mermaid
flowchart TD

%% Colors %%
classDef red fill:#8B0000,stroke:#FFF,color:#FFF
classDef gold fill:#FFCC33,stroke:#FFF,color:#000

%% Jamaal Roberson's Line %%
M210("Jamaal Roberson"):::gold
M210---M237
M237("Joel Philip"):::red
M237---M251
M251("Gian Lezotte"):::red
M251---M266 & M267
M251----M280
M251-----M298
M266("Melchizedec Correa"):::red
M266---M287
M266----M301
M267("Michael Potts"):::red
M267---M292
M280("Avantika Chellury"):::red
M287("Mikayla Wiest"):::red
M292("Shaunak Dabir"):::red
M298("Ryan Crowell"):::red
M301("Olivia Huhn"):::red

%% Co-Relationships & Current Pledges %%
M253("Gavin Nicely")
M263("Elena Hereford")
M263---M280

M292----MP01
M253------MP01
M298---MP03
M301---MP02
MP01("Tristan Alvarez")
MP02("Samantha Merrill")
MP03("Christian Gamez")
```