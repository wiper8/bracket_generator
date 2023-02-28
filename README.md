# bracket_generator
Automatic bracket generator 

# TODO

Bracket image with <16 candidates

main to flush bad candidates. Estimate % of candidates to be flushed, and do N/Y inverse brackets of Y=2^ceil(log_2(1/%))
elements where we select the losers and flush the worst loser. This will take N/Y*(Y-1) comparisons.
