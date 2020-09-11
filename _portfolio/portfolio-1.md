---
title: "Simulating Antigen dosage and key immune cell kinetics using modified explicit tau-leap Gillespie simulation"
excerpt: "Throughout my Ph.D. I've studied how vaccine scheduling modulates the antibody titer response.  
Together with with experimental collaborators, we identified a new cellular mechanism that can potentially amplify   
antibody responses upto 20 times in titers. Based on the mechanistic understanding, I built a stochastic system that  
simulates our body’s antibody responses from a vaccine: [link to code](https://github.com/sunnnymskang/Tau_leap_gillespie_OOP) . <br/><img src='/images/500x300.png'>"
collection: portfolio
---

Vaccination is undoubtedly one of the most effective preventive measures against infectious diseases. 
By exposing our body to pathogentic materials (Antigens) vaccination induces immune response and establishes memory of 
invasion that natural infeciton would do, but in a minute and maneagable scale. Recent development in bio compatible 
materials have promising and positive implications for vaccines, that through engineering the propoerty of vessel 
materials which deliver antigens, immune response - such as antibody quantity can be greatly enhanced. 
In fact, Tam et al, explored vairous antigen delivery kinetics and found that spacing out the dosage into multiple 
smaller dosages results in greater antibody response. Moreover, they also found that if the kinetics in which these 
dosages follow exponentially increasing pattern,it can induce upto 20 times more antibody production. While Tam et al 
paper eludicated the mechanism through which confers more antibody production, namely through antigen availability, 
further study is warranted so as to understand how temporal vaccine kinetics affects affinity maturation through which 
affinity and quantity of antibodies are determined. Affinity maturation is a seqeunce of stochastic events which is in 
essence an accelerated darwinian evolution that leads to stronger affinity antibodies through mutation and seletion cycle. 
In order to understand how dosage kinetics alter affinity maturaiton and to predict the resulting immune response, 
I developed a explicit tau-leap gillespie simulation with a intent of combining this module with stochastic affinity 
maturation simulaiton, previously developed by ShenShen Wang. [Repo](https://github.com/sunnnymskang/Tau_leap_gillespie_OOP)

