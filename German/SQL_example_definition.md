type:
   id: integer
   classification: string
   /*
      control:
            Pull                          # Pulls an neighbored impulse
            adjection                # adjects an Impulse away
            translatoric:           # an translative limit
                propulsive          # blocks impulse till a propulsion occurs
            accumulative:        #definition of how several impulses are joined
                     additive          # joins two impulse intensities
                     subtractive    # differentiates two impulse intensities
             duplicate               # duplicates an impulse to side branch
                 spin left             # spins a cloned impulse to left
                 spin right          # sounds a cloned impulse to right
 
deeper explanation of node controls:
 
 pull: 
 an impulse is pulled from its straight branch to a neighbor branch
 
 adjection:     
 two impulses influence each other in the manor,
 that an adjection effect occurs.
 
 translatoric propulsion:
 until an defined limit isn't accumulated, 
 throughput is blocked.
 
 accumulative addition:
 two impulses are added in intensity together
 
 accumulative subtraction:
 the impulse intensity of two serial impulses is differentiated.
 this is mainly for:
 feeling changes => evaluative emotions=> euphoria
 these separate levels are about independent transmission types
 
 duplicate:
 this use cases are 
A.) for keeping an informative impulse formation,
 through circular movement active
 B.) Differentiation of serial Impulse flows
 
 */
 
 node:
     id:   big integer
     x:    integer
     y:    integer
     z:    integer
     tid: <type id> integer
 
 branch:
      Id:      big integer
      nid1:  <node ID> big integer
      nid2:  <node ID> big integer
      
 Impulse:
    intensity: integer
    range:      integer