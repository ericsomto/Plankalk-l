# Plankalk-l
An Esoteric Programming Language for hardware and 3D graphics rendering

#### Data Structure

    The only primitive objects in the Plankalk~l are of
    the mode bool (or bit), which is denoted by S0;4 they
    are called Ja-Nein-Werte
    Composite objects are built up recursively
    
    in particular arrays of arbitrary dimensions and records
    For example, the array modes [ 0 : n - 1]bool and 
    [ 0 : m - 1, 0 : n - 1]bool are denoted by n X SO and m X n respectively
    If a variable indication ~ (variables Strukturzeichen) a or
    a constant indication $2 is used to denote the first of
    these two modes, then the second can be denoted by
    m X o- or m )< $2, respectively

    There is also the possibility of using the abbreviated notation
    S l . n or S1.8
    instead of n × SO or 8 × S 0 .
    In this case we have a new mode bits of word length n
    or 8, respectively; the array, however, can still be sub-scripted

    A record of, say, two components, which are denoted by some variable or constant indications o,r or
    A2, A3, is specified by (cr,~-) or (A2, A3).
    Here, too, subscripts will be used for the selection of
    components; they always start with zero

    Strukturen for structured values and their
    corresponding modes; he says Art for the conglomerate
    consisting of a Struktur together with its pragmatic
    meaning (Typ) and a possible restriction
    which says which of the elements of a certain
    structure are meaningful. For example, objects of the
    structure, S I . 4 (tetrades)

     Standard denotations for Boolean objects (SO) are
     L and 0
     for bit sequences (for example S 1 . 4 ) 7
     LL00, LOLL.
    F o r integers and numerical-real objects, instead of bit
    sequences, conventional figures can also be used. s
    For the standard denotation of more general, com-
    posite objects, a denotation is used which is now conventional for input and output: 
    The standard denotations of the components of composite objects are listed
    in the specified order, such that the additional mode
    indication for the object allows one to form the decom-
    position uniquely
    
    For clearness only, a special separation mark 
    (semicolons instead of commas) is used for the separation of composite objects

