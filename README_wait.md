```mermaid
flowchart TD

%% --- signifies a line, every additional - signifies another pledge class.
%% example below shows: alpha active has littles in beta (next pledge class)
%% and gamma class (next next pledge class)

P01("Alpha")
P02("Beta")
P03("Gamma")

P01---P02
P01----P03
```

example: sarah (”alpha”) has littles nick (”delta”) and emma (”epsilon”), notice that sarah’s lines are longer because sarah did not pick up a little in the “beta” or “gamma” pledge classes. there are five dashes (’——-’) between her and nick and six (’———’) between her and emma

```mermaid
flowchart TD

%% how to do cobigs (alpha and beta from other line coparenting a little in gamma)

P01("Alpha")
P02("Beta")
P03("Gamma")
P04("Beta (Another Line)")

P01---P02
P01----P03
P04---P03
```

example: kayla (”delta”) and emma (“epsilon”) share deva (”zeta”)

```mermaid
flowchart TD

%% how to do cobigs (alpha and alpha from another line coparenting a little in gamma)

P01("Alpha")
P02("Beta")
P03("Gamma")
P04("Alpha (Another Line)")

P01---P02
P01----P03
P04----P03

%% notice how - have to be equal in amount if two bigs are in the same pledge class
```

example: sarah (”gamma”) and max (”gamma”) share angela (”epsilon”)

```mermaid
flowchart TD

%% how to do cobigs (beta and beta from another line coparenting a little in gamma)

P01("Alpha")
P02("Beta")
P03("Gamma")
P04("Beta (Another Line)")

P01---P02
P02---P03
P04---P03
```
