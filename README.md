# fopExamples

Examples of two protocols implemented locally and globally in IVy.

Leader Election:
  Globally: Axiomatize topology through btw(x,y,z) relation.
  Locally:  Give finite instantiation of axioms on local terms p,next(p),q1,q2,q3. This can be expanded to a local statement
 
RBR Example:
  Globally: Partially axiomatize topology. We say that every process has exactly one colour and a process is colour X iff the left and right neighbours are colour Y (X~=Y). The second statement takes the axiomatization out of the EPR fragment for IVy, losing a termination guarantee.
  Locally:  Describe local neighbourhood right(p),p,left(p),q. Since IVy only gets axiomatization on these terms, terms like left(left(p)) are never considered, keeping the specificiation in EPR, giving us completeness.
