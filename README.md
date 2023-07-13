vscode-custom-css
This is a custom CSS for vscode which adds glowing text and other fun features.


https://www.emastercam.com/forums/topic/103232-unified-morph/

https://www.google.com/search?q=delineation&rlz=1C1GCEA_enUS1057US1057&sourceid=chrome&ie=UTF-8
https://www.emastercam.com/forums/topic/100210-5-axis-tool-paths-and-planes/
https://img1.wsimg.com/blobby/go/d65a7400-ce70-476c-a7a1-cd6f7a422e94/downloads/Handbook%20of%20Mathematics%2C%206th%20Edition%20%5B2015%5D.pdf?ver=1601098685494
https://www.emastercam.com/forums/topic/100202-cylindrical-part-with-radial-pocket-that-has-a-cylindrical-floor-how/
https://www.emastercam.com/forums/topic/103669-safety-zone/
https://www.emastercam.com/forums/topic/90557-having-a-hard-time-understanding-primary-vs-seconary-axis/
https://www.emastercam.com/forums/topic/102760-complex-5-axis-tool-path/
https://www.emastercam.com/forums/topic/89529-3d-toolpath/


import re

# Read the input text or file
with open('input.txt', 'r') as file:
    text = file.read()

# Define the regex pattern
pattern = r'^(?=.*\bG1\b)(?=.*\bF\b).*$'

# Perform the replacement
new_text = re.sub(pattern, r'M50\n\g<0>', text, flags=re.MULTILINE)

# Write the modified text back to the file
with open('output.txt', 'w') as file:
    file.write(new_text)



    line. The pattern could be something like: ^(?=.*\bG1\b)(?=.*\bF\b).*$. This pattern uses positive lookahead assertions (?=...) to ensure that both^(?=.*\bG1\b)(?=.*\bF\b).*$ for this case
