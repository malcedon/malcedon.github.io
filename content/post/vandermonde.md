---
title: Vandermonde's Identity
author: Δαίδαλος
date: 2023-06-16
---

In this post, I will give a short sketch of a proof of Vandermonde's identity, which states that for non-negative integers \( m \), \( n \), and \( r \):

\[
  \binom{m+n}{r} = \sum_{k=0}^{r} \binom{m}{k} \binom{n}{r-k}
\]

## My sketch of the proof

Consider a box containing \( m+n \) balls, of which \( m \) are red and \( n \) are blue. We want to choose \( r \) balls from this box. The left-hand side counts the number of ways to choose \( r \) balls from \( m+n \) total balls. And the right-hand side counts the number of ways to choose \( r \) balls by first choosing \( k \) red balls (where \( k \) can range from \( 0 \) to \( r \)), and then choosing the remaining \( r-k \) balls from the \( n \) blue balls.
