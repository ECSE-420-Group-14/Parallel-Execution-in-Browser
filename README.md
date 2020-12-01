# Parallel-Execution-in-Browser

## Execute the following

emcc lodepng.c  -O2 -s USE_PTHREADS=1 -s PTHREAD_POOL_SIZE=5 -o test.js functions.c --embed-file Test_1.png --embed-file Test_1_output.png 
