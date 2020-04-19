## docker build
~~~sh
cd docker
docker build -t pi_kernel:imx-1 .
~~~
  

## run container
~~~sh
cd docker
./run_container
or
docker run -it --volume="$PWD/build:/workdir/pi" --volume="$PWD/build:/workdir/build" pi_kernel:imx-1
~~~