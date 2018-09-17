---
published: true
layout: post
category: Action
tags: action_unit
comments: true
title: "Action Units - Face (Kor)"
date: 2018-09-14 19:50:25 -0400
---

# Action Units - Face
얼굴영역 분석을 위해, 얼굴과 관련된 액션유닛(action units: AUs)을 정리합니다. 주로 다음 논문을 참고하였습니다.

위키: 
     https://en.wikipedia.org/wiki/Facial_Action_Coding_System
논문: 
     Ekman P. , Friesen W.V. , Hager J. 2002 Facial Action Coding System: Research Nexus Network Research Information
     Tian Y, Kanade T, Cohn JF. Recognizing Action Units for Facial Expression Analysis. PAMI 2001;23(2):97-115. 
     Scherer K, Ekman P. Handbook of Methods in Nonverbal Behavior Research. Cambridge Univ. Press; Cambridge, UK: 1982
     Freitas-Magalhães, A. 2018 Facial Action Coding System 3.0 ISBN 978-989-8766-86-1.

## 개요
AUs는 저명한 심리학자인 Ekman 등이 2002년 출판한 FACS(Facial Action Coding System)에서 찾아볼 수 있으며, 현재 1) Main codes 28개, 2) Head movement codes 14개 등 확장된 형태를 아래 full list에서 살펴볼 수 있습니다. 

## full list of unit actions in face region
### Main codes
0	Neutral face	
1	Inner brow raiser	frontalis (pars medialis)
2	Outer brow raiser	frontalis (pars lateralis)
4	Brow lowerer	depressor glabellae, depressor supercilii, corrugator supercilii
5	Upper lid raiser	levator palpebrae superioris, superior tarsal muscle
6	Cheek raiser	orbicularis oculi (pars orbitalis)
7	Lid tightener	orbicularis oculi (pars palpebralis)
8	Lips toward each other	orbicularis oris
9	Nose wrinkler	levator labii superioris alaeque nasi
10	Upper lip raiser	levator labii superioris, caput infraorbitalis
11	Nasolabial deepener	zygomaticus minor
12	Lip corner puller	zygomaticus major
13	Sharp lip puller	levator anguli oris (also known as caninus)
14	Dimpler	buccinator
15	Lip corner depressor	depressor anguli oris (also known as triangularis)
16	Lower lip depressor	depressor labii inferioris
17	Chin raiser	mentalis
18	Lip pucker	incisivii labii superioris and incisivii labii inferioris
19	Tongue show	
20	Lip stretcher	risorius w/ platysma
21	Neck tightener	platysma
22	Lip funneler	orbicularis oris
23	Lip tightener	orbicularis oris
24	Lip pressor	orbicularis oris
25	Lips part	depressor labii inferioris, or relaxation of mentalis or orbicularis oris
26	Jaw drop	masseter; relaxed temporalis and internal pterygoid
27	Mouth stretch	pterygoids, digastric
28	Lip suck	orbicularis oris

### Head movement codes
51	Head turn left	
52	Head turn right	
53	Head up	
54	Head down	
55	Head tilt left	
M55	Head tilt left	The onset of the symmetrical 14 is immediately preceded or accompanied by a head tilt to the left.
56	Head tilt right	
M56	Head tilt right	The onset of the symmetrical 14 is immediately preceded or accompanied by a head tilt to the right.
57	Head forward	
M57	Head thrust forward	The onset of 17+24 is immediately preceded, accompanied, or followed by a head thrust forward.
58	Head back	
M59	Head shake up and down	The onset of 17+24 is immediately preceded, accompanied, or followed by an up-down head shake (nod).
M60	Head shake side to side	The onset of 17+24 is immediately preceded, accompanied, or followed by a side to side head shake.
M83	Head upward and to the side	The onset of the symmetrical 14 is immediately preceded or accompanied by a movement of the head, upward and turned and/or tilted to either the left or right.

### Eye movement codes
61	Eyes turn left	
M61	Eyes left	The onset of the symmetrical 14 is immediately preceded or accompanied by eye movement to the left.
62	Eyes turn right	
M62	Eyes right	The onset of the symmetrical 14 is immediately preceded or accompanied by eye movement to the right.
63	Eyes up	
64	Eyes down	
65	Walleye	
66	Cross-eye	
M68	Upward rolling of eyes	The onset of the symmetrical 14 is immediately preceded or accompanied by an upward rolling of the eyes.
69	Eyes positioned to look at other person	The 4, 5, or 7, alone or in combination, occurs while the eye position is fixed on the other person in the conversation.
M69	Head and/or eyes look at other person	The onset of the symmetrical 14 or AUs 4, 5, and 7, alone or in combination, is immediately preceded or accompanied by a movement of the eyes or of the head and eyes to look at the other person in the conversation.

### Visibility codes
70	Brows and forehead not visible
71	Eyes not visible
72	Lower face not visible
73	Entire face not visible
74	Unsociable

### Gross behavior codes
These codes are reserved for recording information about gross behaviors that may be relevant to the facial actions that are scored.
29	Jaw thrust	
30	Jaw sideways	
31	Jaw clencher	masseter
32	[Lip] bite	
33	[Cheek] blow	
34	[Cheek] puff	
35	[Cheek] suck	
36	[Tongue] bulge	
37	Lip wipe	
38	Nostril dilator	nasalis (pars alaris)
39	Nostril compressor	nasalis (pars transversa) and depressor septi nasi
40	Sniff
41	Lid droop	Levator palpebrae superioris (relaxation)
42	Slit	Orbicularis oculi muscle
43	Eyes closed	Relaxation of Levator palpebrae superioris
44	Squint	Corrugator supercilii and orbicularis oculi muscle
45	Blink	Relaxation of Levator palpebrae superioris; contraction of orbicularis oculi (pars palpebralis)
46	Wink	orbicularis oculi
50	Speech
80	Swallow
81	Chewing
82	Shoulder shrug
84	Head shake back and forth
85	Head nod up and down
91	Flash
92	Partial flash
97*	Shiver/tremble
98*	Fast up-down look
