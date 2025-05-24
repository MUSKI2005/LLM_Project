# LLM_Project
<!-- # Importing torch -->
<!-- checking randint with torch.randint -->

<!-- Tensor with torch.tensor -->
<!-- Getting the matrix of zeros of 2 rows and 3 columns -->

<!--making matrix of zeros with torch.zeros(2,3) -->

<!--making matrix of ones with torch.ones -->

<!--using arange with torch.arange(5) -->

<!-- linspace with torch.linspace -->
<!-- logspace with torch.logspace -->

<!-- eye with torch.eye(5) -->

<!-- a with torch.empty((2, 3), dtype=torch.int64) -->

## IMPORTING time
## import numpy as np

<!-- print("CUDA Available:", torch.cuda.is_available()) -->
<!-- print("Torch Version:", torch.__version__) -->
<!-- print("Device Name:", torch.cuda.get_device_name(0) if torch.cuda.is_available() else "No GPU") -->

*Block Size equals to 8*
*Batch size equals to 4*

<!-- start_time=time.time() -->

## matrix operation here

<!-- zeros=torch.zeros(1,1) -->
<!-- end_time=time.time() -->

## navdia is not supported in windows 11 so we are better using CPU instead if GPU
## Therefore it might take some time

<!-- elapsed_time=end_time-start_time -->
<!-- print(f"{elapsed_time:.8f}") -->

<!-- with open('wizardLLM.txt','r',encoding='utf-8') as f: -->
<!-- for reading the file -->
<!-- text=f.read() -->

<!--  NOW for printing the 1st 200 texts -->
<!-- print(text[:200]) -->

<!-- now making a sorted array set for the characters -->
<!-- chars=sorted(set(text)) -->

<!-- print(chars) -->
<!-- printing the length of chars -->
<!-- print(len(chars)) -->

*string to int conversion*
*int_to_string*
<!-- encoding using lambda function for string -->
<!-- encode=lambda s:[string_to_int[c] for c in s] -->

<!-- Decode using lambda function for string -->
<!-- decode=lambda l: ''.join([int_to_string[i] for i in l])
 -->

<!-- encoded hello with encode function -->
<!-- encoded_hello=encode('hello') -->

<!-- decode hellousing decode function -->
<!-- decoded_hello=decode(encoded_hello) -->

*print(decoded_hello)*

## validation and training space
<!-- EXAMPLE -->
<!-- n=int(0.8*len(data)) -->
<!-- train_data=data[:n] -->
<!-- val_data=data[:n] -->

*training is 80% and last 20 % for validation,  for the text corpus*
*using training and validation splits
*

<!-- taking block size -->
<!-- block_size=8 -->

<!-- X is for training data set on block size-->
<!-- x=train_data[:block_size] -->

<!-- y is for testing the data over blocksize -->
<!-- y=train_data[1:block_size+1] -->


