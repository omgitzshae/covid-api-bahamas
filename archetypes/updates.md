---

islands:
  np: &np New Providence
  gb: &gb Grand Bahama
  el: &el Eleuthera
  ab: &ab Abaco
  ex: &ex Exuma
  an: &an Andros
  bim: &bim Bimini
  li: &li Long Island & Rum Cay
  bi: &bi Berry Islands
  ci: &ci Cat Island
  in: &in Inagua
  ss: &ss San Salvador
  ac: &ac Acklins
  cr: &cr Crooked Island
  ma: &ma Mayaguana
  # ri: &ri Ragged Island
  rc: &rc Rum Cay

title: {{ replace .Name "-" " " | title }}
weight: {{ replace .Name "-" " " | title }}
date:

update:

  number: {{ replace .Name "-" " " | title }}

  full: 

  abroad: 

  pfizer: true
  pfizernote: Pfizer two dose vaccination introduced to numbers between Saturday, Aug 07, 2021 and  Saturday, Aug 14, 2021 period.

  jj: true
  jjnote: Johnson & Johnson single dose vaccination introduced to numbers between Sat, Sep 4, 2021 and Fri, Sep 10, 2021 period.
  
  doses:

    aggregate:
      total: 
      first: 

    byIsland:
      - island:
          name: *np
          first: 
          second: 0
      - island:
          name: *gb
          first: 
          second: 0
      - island:
          name: *el
          first: 
          second: 0
      - island:
          name: *ab
          first: 
          second: 0
      - island:
          name: *ex
          first: 
          second: 0
      - island:
          name: *an
          first: 
          second: 0
      - island:
          name: *bim
          first: 
          second: 0
      - island:
          name: *li
          first: 
          second: 0
      - island:
          name: *bi
          first: 
          second: 0
      - island:
          name: *ci
          first: 
          second: 0
      - island:
          name: *in
          first: 
          second: 0
      - island:
          name: *ss
          first: 
          second: 0
      - island:
          name: *ac
          first: 
          second: 0
      - island:
          name: *cr
          first: 
          second: 0
      - island:
          name: *ma
          first: 
          second: 0
    #   - island:
    #       name: *rc
    #       first: 
    #       second: 0

draft: true
---

