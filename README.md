# Target

....

Cli paramaters

``` sh
    [usage] 
    node index.js -in [input_folder] -out [output_folder]
```

Requirements:
1. wrong format ( missing in, out )
    Print [usage] node index.js -in [input] -out [outputs]
2. Correct format
    Check input folder existed ? => print "input folder not found"
3. Check if output folder existed => Asking question ( do you want to delete ) ?
    Yes -> delete
    No -> exit ko lam zi het
4. xu ly hinh -> waiting all complete -> exit
    Co error -> delete output foder -> display error 

# Instalation

``` sh
npm install
```