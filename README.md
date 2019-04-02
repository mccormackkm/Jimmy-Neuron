# Jimmy-Neuron
CS 4884 Computing the Brain Capstone

# Running MCL
pull repo and go into \MCL\mcl-14-137 and run ./configure --prefix={PATH} to set where {PATH} is where you want the executables to be installed. Then run make clean/make and then make install. it should drop executables in {PATH}/bin. mcl executable will be there. To test, run:
mcl {input_filename} -o {output_filename} -abc.
input_filename should be in format of:

NodeA NodeB Weight  
NodeC NodeD Weight  
NodeE NodeF Weight  

NodeA and NodeB can be text, Weight must be numeric. Each line is an edge between any two nodes.  
More information/Documentation: https://www.micans.org/mcl/index.html?sec_software  
