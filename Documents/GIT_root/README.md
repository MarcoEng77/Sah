Just playing around with .pgn parsers and a Stockfish Python API.
The idea is to formulate an "entropy" metric for openings, mutuated from statistical physics. Intuitively, openings allowing wider trees, where each move is weighted according the number of children moves, each in turn weighted by its strength, have a higher entropy. 
