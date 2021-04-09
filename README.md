# Thompson's construction
Thompson's construction is algorithm for convert regex (regular expression) to NFA (Non-deterministic Finite Automata).
This is usally used in lexical analyzing step of compiler.
To categorize lexemes to tokens, we need DFA (Deterministic Finite Automata).
So, lexer need to convert NFA to DFA, and 'subset construction' do this well.
