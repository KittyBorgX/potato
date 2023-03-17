# potato
Who said python couldn't have nice errors? 


### When will work start on this? 
Heavy and serious development will start from next week :) (Somewhere around 25th March, 2023)

### Running
```
git clone https://github.com/KittyBorgX/potato.git
cd potato
cargo build --release
./target/release/potato test.py # Assuming your file is `test.py`
```

### How do I achieve this? 
* Capture output of the python process by running the file provided
* Parse the output and look for any errors
* Format the errors using ariadne/codespan-reporting and display them back
