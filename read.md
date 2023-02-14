
# nd013-scan-matching-localization

## Project Workspace

## Compile

cd /home/workspace/c3-project
<br>
cmake .
<br>
make
<br>
<br>

## Run

su - student // Ignore Permission Denied, if you see student@ you are good
<br>
cd /home/workspace/c3-project
<br>
./run_carla.sh
<br>
// Create new tab
<br>
cd /home/workspace/c3-project
<br>
./cloud_loc // Might have core dump on start up, just rerun if so. Crash doesn't happen more than a couple of times
<br>
<br>
<br>
<br>


## Vehicle driving and error screenshots after implementing ICP
<br>
<br>

### 3 iterations
<br>
<br>
![This is an image](images/c3_icp_lidar_3_iterations_a.png)

<br>
<br>
![This is an image](images/c3_icp_lidar_3_iterations_b.png)


### 9 iterations
<br>
<br>
![This is an image](images/c3_icp_lidar_9_iterations_a.png)
<br>
<br>
![This is an image](images/c3_icp_lidar_9_iterations_c.png)

<br>
<br>
<br>
<br>
