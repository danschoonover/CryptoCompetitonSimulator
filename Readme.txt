This python notebook simulates a prize distribution (ie payout scheme) for a competition - in the seminal example, a fitness challenge. 

Participants each pay a fixed fee into a common pool, that prize pool is then distributed after the comptition as a function of particpants ranking in the competition, and following:
1) Competitors who rank highest should receive the largest payouts 
2) lower-ranking competitors should still received some real/positive payout 
3) all competitors should be incentivized to participate and to re-enroll in future competitions via these winnings

The harmonic series was found to be a good fit for this criteria, and therefore used in this script.
