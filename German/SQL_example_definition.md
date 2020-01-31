# SQL example definition

----

## Type:  

```SQL
-- Table for specifications of node types 

id: integer  			-- Primary Key
classification: string  -- see Description Section at Bottom of this Doc

```



## Node:  

```SQL
 --  Node Table as replacement for neurons 
 
 id:   big integer  -- Primary Key
 x:    integer   	-- Spatio-coord Axe
 y:    integer  	-- Spatio-coord Axe
 z:    integer      -- Spatio-coord Axe
 tid:  integer  	-- Foreign Key to <Type id>
```



## Axon:   

```SQL
  -- Axon Table
  Id:   big integer   -- Primary Key
  nid1: big integer   -- Foreign Key to <Node ID> 
  nid2: big integer   -- Foreign Key to <Node ID> 
```



## Impulse:   

```SQL
intensity:  integer -- Descriptive scalar Value of Impulse  
range:      integer -- Optional Value describing the area of influence 
```



----

## Explanations:

-----



##	type definitions for classification String

 + pull                   Pulls an neighbored Impulse  
 + adjection              adjects an Impulse away  
 + translatoric:          an translative limit  
   + propulsive           blocks Impulse till a propulsion occurs  
   + generative		   Emitts an defined Impulse Intensity
 + accumulative:          definition of how several Impulses are joined  
     + additive             joins two Impulse intensities  
     + subtractive          differentiates two Impulse intensities  
 + duplicate              duplicates an Impulse to side Axon  
     + spin left            spins a cloned Impulse to left  
     + spin right           sounds a cloned Impulse to right  

---



 ## deeper explanation of node controls

---

#### pull:  

An Impulse A is pulled  
from its straight Axon  
to a neighbor Axon  
by being triggered  
by an simultaneous Impulse B,  
pulling Impulse A to its Axon away. 

---



#### adjection:     

Two Impulses influence each other in that manor,  
as an adjection effect occurs.  

----



#### translatoric propulsion:

Until an defined limit  
isn't accumulated (in time),   
Impulse throughput is blocked.   

---



#### translatoric generative:

If an Impulse is reaching,  
then it is translated in Intensity,   
as those new Impulse (re)generates the Information.

---



#### accumulative addition:

Two Impulses are added in intensity together,  
and are mostly combined to a translatoric Propulsion.

---



#### accumulative subtraction:  

The Impulse intensity  
of two serial or  
parallel Impulses  
is differentiated.   
This is mainly for:  

*  L1:  "feeling changes" 
*  L2:  "evaluative emotions" 
*  L3:  "euphoria" or "disgusting pain"  

These separate levels  
are about to be used  
by independent Node types and  
for subconscious evaluation.
(affective motivation Principles)

---



#### duplicate:  

The use cases here are:

A. For keeping an informative Impulse formation active    
    by a circular movement active  

B. Differentiation of serial Impulse flows  
    in purposes of (sub)conscious evaluation.

Furthermore,  
the spinning defines the information flow and  
could be of use to  
separate different flow types.
