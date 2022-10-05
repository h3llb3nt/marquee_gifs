# marquee_gifs
collection point for art for tty2rgbmatrix, web2rgbmatrix, etc

i have no idea what i'm doing. suggestions?  
  
I would just create two folders, one for static gif, one for animated gifs.

I think filename should match what MiSTer reports as the core. ie. Minimig.gif - kconger

Should we consider future resolutions? Maybe the top level folder would be the resolution. ie. 128x32 - kconger

I would suggest subfolders for each number/letter as well, I've found the SD library can take forever to list large directories. A large single directory takes minutes to list and breaks both FTP Server libraries I've tried.  Below illustrates my suggestion. - kconger

```
.
├── animated
│   ├── 0
│   ├── 1
│   │   └── 1944.gif
│   ├── 2
│   ├── 3
│   ├── 4
│   ├── 5
│   ├── 6
│   ├── 7
│   ├── 8
│   ├── 9
│   ├── A
│   ├── B
│   ├── C
│   ├── D
│   ├── E
│   ├── F
│   ├── G
│   ├── H
│   ├── I
│   ├── J
│   ├── K
│   ├── L
│   ├── M
│   ├── N
│   ├── O
│   ├── P
│   ├── Q
│   ├── R
│   ├── S
│   ├── T
│   ├── U
│   ├── V
│   ├── W
│   ├── X
│   ├── Y
│   └── Z
└── static
    ├── 0
    ├── 1
    │   └── 1944.gif
    ├── 2
    ├── 3
    ├── 4
    ├── 5
    ├── 6
    ├── 7
    ├── 8
    ├── 9
    ├── A
    ├── B
    ├── C
    ├── D
    ├── E
    ├── F
    ├── G
    ├── H
    ├── I
    ├── J
    ├── K
    ├── L
    ├── M
    ├── N
    ├── O
    ├── P
    ├── Q
    ├── R
    ├── S
    ├── T
    ├── U
    ├── V
    ├── W
    ├── X
    ├── Y
    └── Z
```
