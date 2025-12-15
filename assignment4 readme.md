AI-ML-Assignment-4-Generative-LLM
Oliver Warlick
YouTube Video: https://youtu.be/mH0AmZJqphU

The specific Large Language Model (LLM) used: Mistral 7B
Chosen task: Generation

Summary: 


Parameter Value (Temperature): 0.2 (Low Randomness)	
Output Snippet: "In the heart of the quaint, cobblestoned town of Briarwood, nestled between the labyrinthine lanes and the hallowed halls of history, resided a man of peculiar passions and unquenchable curiosity. His name was Edgar Montrose..."	
Generation time: 206.17s	
Brief Observation: Highly formal, predictable, and cohesive. The model chose the most probable words, resulting in the slowest generation time (due to exhaustive search) but the most structured prose.

Parameter Value (Temperature): 0.7 (Moderate Randomness)	
Output Snippet: "In the heart of the bustling city of London, nestled amidst the labyrinthine network of cobblestone streets and quaint, ivy-covered houses, lies an unassuming antique shop, known to a select few as the 'Sanctum of Time.'..."	
Generation Time: 110.53s	
Brief Observation: Strong balance between structure and creativity. The tone is engaging, and the model introduced a novel element ("Sanctum of Time"). This represents the sweet spot for balancing quality and speed.

Parameter Value (Temperature): 1.0 (High Randomness)	
Output Snippet: "In the quaint, cobblestone alleys of Old Town, where antique shops bloomed like ancient roses among the cobwebs of time, resided a man named Edgar. An ardent collector of ornate antique clocks, his home was a labyrinth of gears..."	
Generation Time: 105.79s	

Brief Observation: Highly creative, poetic language, and striking metaphors ("bloomed like ancient roses," "harmonious discord"). The model quickly selected tokens from a wider distribution, resulting in the fastest generation time but the most abstract language.
