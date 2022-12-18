Deutsch-Jozsa Algorithm

Run the 'run(N, case, sim)' defined in the file at the end of the jupyter notebook of the Deutsch-Jozsa algorithm 

Input:
    N - number of bits in input bit string of the function f
    case - type of function to be given as a string either 'constant' or 'balanced'
    sim: simulator on which you want to run the algorithm
          1: non-noisy aer simulator
          2: non-noisy qasm simulator
          3: noisy simulator FakeJakarta
          4: noisy simulator FakeBelem
Output: counts, if maximum counts is for '0'*N, the function is constant
                if maximum counts is for '1'*N, the function is balanced

Bernstein-Vazirani algorithm

Run the 'run(secret_num, sim)' defined in the file at the end of the jupyter notebook of the Bernstein-Vazirani algorithm

Input:
    secret_num - the secret string(to be encoded as black box)
    sim: simulator on which you want to run the algorithm
        1: non-noisy aer simulator
        2: non-noisy qasm simulator
        3: noisy simulator FakeJakarta
        4: noisy simulator FakeNairobi

Output: counts, maximum number of counts are obtained for the secret string

Simon's Algorithm

Run the 'run(a, sim)' defined in the file at the end of the jupyter notebook of the Simon's algorithm

Input:
    a - the bitstring(to be encoded as black box)
    sim: simulator on which you want to run the algorithm
        1: non-noisy aer simulator
        2: non-noisy qasm simulator
        3: noisy simulator FakeJakarta
        4: noisy simulator FakeNairobi
    
Output: counts, maximum number of counts are obtained for the linearly independent strings

Grover's Algorithm

Run the 'run(inp_str, sim)' defined in the file at the end of the jupyter notebook of the Grover's algorithm

Input:
    inp_str - the input string corresponding to f(x) = 1
    sim: simulator on which you want to run the algorithm
        1: non-noisy aer simulator
        2: non-noisy qasm simulator
        3: noisy simulator FakeJakarta
        4: noisy simulator FakeBelem
Output: counts, maximum number of counts are obtained for the secret string
