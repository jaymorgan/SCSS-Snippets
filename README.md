SCSS-Snippets
=============

These are my SCSS & Compass Snippets for SublimeText2. I haven't been happy with any other ones out there, so I'm starting my own.


## Current Snippets

### Trigger:
`active`

### Expands as:
    &:active{
        ${1:this}
    }

---

### Trigger:
`im`

### Expands as:
    @import "${1}";

---

### Trigger:
`in`

### Expands as:
    @include ${1};

---

### Trigger:
`im`

### Expands as:
    @import "${1}";

---

### Trigger:
`mix`

### Expands as:
    //     
    // $1   
    //   
    @mixin ${1:mixin-name}${2:(${3:\$params})} {   
      $0   
    }

_I borrowed this one from another project. I need to give credit for that_

---

### Trigger:
`bg`

### Expands as:
    background:${1:${2:transparent} image-url('${3:image.png}') ${4:left} ${5:top} ${6:no-repeat}};";

---

### Trigger:
`cols`

### Expands as:
    @include column-count(3);   
    @include column-gap($padding);

---

### Trigger:
`hover`

### Expands as:
    &:focus,
    &:hover{
    	${1:this}
    }

---

### Trigger:
`bshad`

### Expands as:
    @include box-shadow(${1:rgba(black, 0.3)} ${2:0px} ${3:0px} ${4:0px});

---

### Trigger:
`tshad`

### Expands as:
    @include text-shadow(${1:rgba(black, 0.3)} ${2:0px} ${3:0px} ${4:0px});

---

### Trigger:
`bobox`

### Expands as:
    @include box-sizing(border-box);

---


## Coming Soon

Going to be adding more as I go. I'm interested in working with someone to grow this to more of the Compass and SCSS mixins.

###_Cheers_


