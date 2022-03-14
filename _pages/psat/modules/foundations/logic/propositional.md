---
permalink: /psat/modules/foundations/logic
title: Assessment
---

# Logic

* What is logic?
  * To put it simply, it's figuring out if a statement is exactly true or exactly false. It's the process of removing any ambiguity!
  * In the PSAT you will encounter *ambiguity*: some answers will *seem* correct, you could possibly feel comfortable selecting any choices listed.
  * We can use logic to come to a correct answer faster.

* In this lesson we will review "propositional logic", a form of logic involving "propositions"

## Propositional Logic

* Propositional logic
  * First off, what is a proposition?
  * It is a **declarative** sentence. Is either **True** or **False**. Not a question, and not a command!
  > ex: "The sky is blue."
  > ex: "My name is Timmy."
  * We can use letters (variables) to represent these sentences!
  > ex: p = "The sky is blue."
  > ex: q = "My name is Timmy."

* We can evaluate these propositions as either **true** or **false** based on reality!
  > ex: "My name is Timmy" is False (F)
  > ex: "My name is Farukh" is True (T)

* This applies to Math too!
  > ex: x > 5, x = 3 is False! (F)

## Propositional Logic Practice

> The Earth is flat.  

1. What is the truth value of this sentence?

* (A) True 
* (B) False

> x = 6    

2. What is the truth value of this sentence given `x > 5`.

* (A) True 
* (B) False

> x = -1    

3. What is the truth value of this sentence given `x < 100`

* (A) True 
* (B) False

> The last letter of today's day is y  

4. What is the truth value of this sentence?

* (A) True 
* (B) False

5. Which one of these sentences is a proposition.

* (A) Clean your room!
* (B) Is that your dog?
* (C) Nice bike!
* (D) The tea is hot.

## Logical Operators

* We can combine these propositional variables using *operators*, just like we can combine numerals using *operators*. The basic operators are:
  * negation (not)
  * conjunction (and)
  * disjunction (or)
  * conditional (implies)

* Negation 
  * In math we represent this as `-p`.
  * This operator gets the opposite truth value of the proposition.
    > ex: "The tea is hot" is true  
    > Therefore the "the tea is not hot" is false (ouch)  
  * This can be translated linguistically in English in multiple ways
    * The insertion of a single negative word (not, don't, didn't, won't)
    * "No" in response
      > ex: Is your cat friendly?  
      > No. (My cat is not friendly)  
  * What do you think happens with multiple negations?
    > ex: "The tea is hot" is true  
    > What is the value of "The tea is not not not not hot."  

* **Con**junction (emphasis on the con)
  * In math we represent this with the carrot symbol `p ^ q`
  * This is the English "and". We join two propositions together!
    > ex: "The tea is hot and my cat is friendly."  
  * This makes a new truth value, given the truth values of the individual propositions!
  * Let's consider what this makes 
    > ex: "The tea is hot" is true  
    > "The cat is friendly" is true  
    > What is the truth value of "The tea is hot and the cat is friendly"?  
  * What if one of these is false?
    > ex: "The tea is hot" is true  
    > "The cat is friendly" is false  
    > What is the truth value of "The tea is hot and the cat is friendly" now?  
  * This gives us this truth table (something we use to map out truth values):

    | p | q | p^q |
    | - | - | --- |
    | T | T |  T  |
    | T | F |  F  |
    | F | T |  F  |
    | F | F |  F  |

    False statements are "sticky" in conjunctions. Once something is false, the entire statement is false!

    Think of it like a contract, if you hear:
    > "You will get a burger, a drink, and french fries"  
    But are missing your drink, the statement turned out to be false and needs to be corrected!

* **Dis**junction (emphasis on the dis)
  * In math we represent this with the seperator symbol `p v q`
  * This is the English "or". Two propositions are still joined but in a different manner!
    > ex: "The tea is hot or my cat is friendly."  
  * Let's consider what this makes 
    > ex: "The tea is hot" is true  
    > "The cat is friendly" is true  
    > What is the truth value of "The tea is hot or the cat is friendly"?  
  * What if one of these is false?
    > ex: "The tea is hot" is true  
    > "The cat is friendly" is false  
    > What is the truth value of "The tea is hot or the cat is friendly" now?  
  * This gives us the table:  

    | p | q | pvq |
    | - | - | --- |
    | T | T |  T  |
    | T | F |  T  |
    | F | T |  T  |
    | F | F |  F  |

    True statements are "sticky" in disjjunctions. Once something is true, the entire statement is true!

    Think of it like a contract, if you hear:
    > "You will get a puppy or a kitten"  
    But you are missing your kitten, it is still true! Or if you get both it is true! But if you get
    neither it is false.

## Operators Practice

> p = T  
> q = F  
> x = T  
> p v q v x  

1. What is the truth value of this sentence?

* (A) True 
* (B) False

> p = T  
> q = F  
> x = T  
> p ^ q ^ x  

2. What is the truth value of this sentence?

* (A) True 
* (B) False

> p = F  
> \- ( - (- p))  

3. What is the truth value of this sentence? 

* (A) True 
* (B) False

> p = T  
> q = F  
> x = T  
> p v q ^ x  

4. What is the truth value of this sentence?

* (A) True 
* (B) False

5. Which one of these sentences is a conjunction?

* (A) Clean your room and walk the dog!
* (B) The phone is on and the sky is blue.
* (C) The phone is on or the sky is blue.
* (D) The phone is not on.

6. Which one of these sentences is a disjunction?

* (A) If the phone is on, the dog is sad.
* (B) The phone is on or the sky is blue.
* (C) The phone is on and the sky is blue.
* (D) Clean your room or walk the dog!

7. Which one of these sentences is a negation?

* (A) The bus not on time.
* (B) The bus is on time.
* (C) The bus is on time or it is not.
* (D) The tea is hot.

> p = T  
> p v \-p  

7. What is the truth value of this sentence?

* (A) True
* (B) False

> p = T  
> p ^ \-p  

8. What is the truth value of this sentence?

* (A) True
* (B) False

> x = 10

9. What is the truth value of this sentence given `x > 5 ^ x < 10`.

* (A) True
* (B) False

> x = 11  

10. What is the truth value of this sentence given `x > 5 v x < 10`.

* (A) True
* (B) False


## Conditionals

* In math we represent the arrow symbol `p → q`.
  * This is the English "if p then q". 
    > ex: "If it rains, I wear a raincoat."  
  * We give special names to each variable this time:
    * p is the *hypothesis*
    * q is the *conclusion*
  * Let's consider what this makes 
    > ex: "it rains" is true  
    > "I wear a raincoat" is true  
    > What is the truth value of "If it rains, I wear a raincoat"?  
  * What if the ending is false?
    > ex: "it rains" is true  
    > "I wear a raincoat" is false  
    > What is the truth value of "If it rains, I wear a raincoat" now?  
  * What if the beginning is false?
    > ex: "it rains" is false  
    > "I wear a raincoat" is true  
    > What is the truth value of "If it rains, I wear a raincoat" now?  
  * What if both are false?
    > ex: "it rains" is false  
    > "I wear a raincoat" is false  
    > What is the truth value of "If it rains, I wear a raincoat" now?  
  * This gives us the table:

    | p | q | p→q |
    | - | - | --- |
    | T | T |  T  |
    | T | F |  F  |
    | F | T |  T  |
    | F | F |  T  |

    Think of it like a contract, if you hear:
    > "If you get an A, you will be top of your class."  
    The only time this is false is if you get an A, and you do not get top of your class!
    If p is fulfilled, then q must be fulfilled.

* Different ways of expressing a conditional
  * “if p, then q” 									  
  * “p implies q” 
  * “if p, q” 									    
  * “p only if q”
  * “p is sufficient for q” 					      
  * “a sufficient condition for q is p”
  * “q if p” 								           
  * “q whenever p”
  * “q when p” 								
  * “q is necessary for p”
  * “a necessary condition for p is q”					     
  * “q follows from p”
  * “q unless ¬p”

* Other types of conditionals, assuming `p → q` is true
  * *converse* `q → p`
  * *inverse* `-p → -q`
  * *contrapositive* `-q → -p`
  * Which one of these are always equivalent to the conditional? Let's compare:

  | p | q | -p | -q | p→q | q→p | -p → -q | -q → -p |
  | - | - | -- | -- | --- | --- | ------- | ------- |
  | T | T |  F |  F |  T  |  -  |    -    |    -    |
  | T | F |  F |  T |  F  |  -  |    -    |    -    |
  | F | T |  T |  F |  T  |  -  |    -    |    -    | 
  | F | F |  T |  T |  T  |  -  |    -    |    -    |

  * What does this mean linguistically:
    * If someone tells you "If I give you $5, you will give me a bagel."
    * The only thing you can guarantee is this: "If I did not give you a bagel, you did not give me $5."
    * We CANNOT guarantee: "If I give you a bagel, you will give me $5."
    * We CANNOT guarantee: "If you do not give me $5, I do not give you a bagel."

## Conditionals Practice

1. Using a truth table: figure out which logical sentence is equivalent to `p → q`

  * (A) `-p v q`
  * (B) `-p v -q`
  * (C) `p v q`

2. If I tell you, "If you plant a seed, a tree will grow." is true. Which one of these is not guaranteed to be true.

 * (A) "If a tree grew, you planted a seed."
 * (B) "If you do not plant a seed, a tree will not grow."
 * (C) "If a tree did not grow, you did not plant a seed."

> Most of us probably know the concept of diversification from the perspective of finance. Savvy   
> investors usually don't put all their eggs into one basket. Diversification also occurs when we  
> buy consumer goods. In that domain, however, diversification isn't always the most advantageous  
> strategy. Have you ever opted for variety in purchasing a month's supply of breakfast cereal, only  
> to later regret not having chosen more boxes of your favorite cereal?  
> ...   
> The simple takeaway for savvy consumers: if you want to choose optimally, make your choices on an  
> as-needed basis. If that's not practical, don't over-diversify if there are significant intervals  
> between consumption. One of the remaining questions, then, is this: how do the laboratory findings  
> on consumption spacing translate into real life? For example, how many hours, days or weeks make  
> for a meaningful gap that would prevent the average consumer from growing tired of eating the same  
> cereal? For individual consumers, only experience will tell.  

3. According to the passage, diversification bias is most likely to occur when consumers

* (A) base consumption on current needs
* (B) attempt to make an impression on others
* (C) try to anticipate future needs
* (D) make choices in response to stress

4. According to the passage "if you want to choose optimally, make your choices on an as-needed basis." What other statements are guaranteed if this is true?

* (A) "If you do not want to choose optimally, do not make choices on an as-needed basis."
* (B) "If you do not make choices on an as-needed basis, you do not want to choose optimally."
* (C) "If you make your choices on an as-needed basis, you want to choose optimally."

5. Which one of these phrases imply a conditional

* (A) p if and only if q
* (B) p and maybe q
* (C) q when p
* (D) q and always p


## Tying it to the PSAT

Dotting questions here and there in this modules practice were questions similiar to those that will show up to the PSAT. A good command of logic will allow a test-taker to better understand a question, and in turn, find the answer faster.

Not only that, but it is an essential for some studies in higher academics, and will only help! 

