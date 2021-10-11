∈<br>
!∈<br>
∅<br>
⊆<br>
⊂<br>
⇔ - if and only if;<br>
⇒  - implies; if ... then ...<br>
≈<br>
≠ - not equal<br>
: - ... such that ... (такой что...)<br>
×<br>
∀<br>
***

**Set** - определенное множество элементов. <br>
! If **x** belongs to the set **A**, we shal say **x** is an element of **A**. **x ∈ A**.<br>
The sets with the same members are equal.<br>
 ∅ - Empty set. <br>
 Subset: A ⊆ B ⇔ ∀x[x ∈ A ⇒ x ∈ B] <br>
 Proper subset: if A≠B : A ⊂ B

 Set can be describe:
 1. By enumeration of the symbols of the set members:
 - A = {1,3,4,7,8}
 - B = {'peter', 'lisa'}
 2. By description of the set distinctive predicate:
 - {x: P(x)} or {x| P(x)}
 - B = {x | x is odd}
 3. By specifying a set, which is already definded, and an additional property which characterizes the necessary and sufficient condition for an element ot belong to the current set:
 - D = {n ∈ N: n <= 5} = {1,2,3,4,5}

**Russell's paradox**:<br>
Обычные множества - которые не содержат себя в качестве элемента
Необычные множества - наоборот)

Множество А, состоящее только из обычных множеств называют **расселовским множеством**.

Если А расселовское множество, то оно содержит только обычные множества.
Если А - обычное множество, то оно должно содержать себя в качестве элемента, что делает его необычным множеством.
Если А - необычное множество, то оно содержит себя, но тогда не выполняется условие того, что оно должно содержать только обычные множества, так как является необычным.


## 2. Relations
Let A and B be not-empty sets, then every subset of A × B defines a relation from A to B<br>
Every relation from A to B is a subset of A × B.<br>
Let R ⊆ A×B and (a,b) ∈ R. Then we say that a is related to b by the relation R and write it as aRb.<br>
If (a,b) ∈ R => aRb

**Total number of relations** = 2^(nm); n - size of A set, M -size of B set.

**Domain of a relation** - Dom(R)={a: (ab) ∈ R}<br>
**Range of a relation** - Range(R)={b: (ab) ∈ R}<br>

**Inverse relation** - Let A, B be two sets and let R be a relation from A to B.<br>
**R^(-1)** is a inverse relation of R. R^(-1)={(b,a):(a,b) ∈ R}<br>
Dom(R) = Range(R^(-1))<Br>
Range(R) = Dom(R^(-1))<br>

**Empty relation** - R ⊂ A×A is empty when R = ∅<br>
 A = set of all students in a girls school<br>
 R = {(a,b): a and b are brothers} - R is empty.

**Universal relation** - R ⊂ A×A is universal if R = A;

**Reflexive** - R ⊂ A×A is reflexive if (a,a) ∈ R for every a ∈ A

**Symmetric** - R ⊂ A×A is symmetric if for ∀(a1,a2) ∈ R: (a2, a1) ∈ R;

**Transitive** - R ⊂ A×A is Transitive if for ∀ a1, a2, a2: (a1,a2) ∈ R && (a1,a2) ∈ R & (a1,a2) ∈ R













