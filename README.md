# cs3630-project-4-particle-filter-implementation-in-webots-simulator-solved
**TO GET THIS SOLUTION VISIT:** [CS3630 Project 4-Particle Filter Implementation in Webots Simulator Solved](https://mantutor.com/product/cs3630-project-4-particle-filter-implementation-in-webots-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112731&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3630 Project 4-Particle Filter Implementation in Webots Simulator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
SIMULATOR

In Project 4, you will implement a particle filter in the Webot simulator. It builds upon the foundation established in prior labs, emphasizing on:

1. Coordinate Transformation: To understand and implement coordinate transformations between the world frame, sensor frame, and robot frame to enable accurate localization and perception in robotics tasks.

2. Differntial Drive: To understand and implement the kinematics of a differential drive robot.

3. Detection Failure and Spurious Detection Handling: To develop strategies to address detection failures and spurious detections, ensuring reliable performance of robotic perception systems in challenging scenarios.

4. Operating in Ambiguous Environments: To explore techniques for navigating larger environments with strong ambiguity, including solving the kidnapped robot problem, to enhance adaptability and robustness in real-world robotics applications.

A. Project Structure:

The project directory, Project_4 contains the following files:

Worlds:

• simple_world.wbt:1 A simple square world for testing the particle filter. (Ref. Figure 1b)

Controllers:

• proj4_simple_world1_controller.py: Controls the robot to turn in-place in the center in the simple world.

• proj4_maze_world1_controller.py: Controls the robot’s movement along a predefined trajectory in the maze world.

Particle_filter:

• contour.py: Deals with extracting contours from camera images.

• geometry.py: Contains functions related to geometric calculations and transformations.

• gui.py: Creates a Graphical User Interface (GUI) for visualizing the particle filter simulation.

• particle_filter.py: Has the particle filter algorithm.

• run_pf.py: Reads captured data in “data” folder and run particle filter without Webots simulator.

• sensors.py: Contains functions related to converting sensor data for the particle filter algorithm.

• setting.py: Holds various configuration settings used throughout the project.

• utils.py: Contains utility functions commonly used in the project.

• unit_tests.py: Contains unit tests for functions in geometry.py, environment.py. It doesn’t test the implementation of particle filter.

B. General Guidance:

• You will implement functions in order in geometry.py, environment.py, and particle_filter.py.

• Refer to the comments in each TODO for specific implementation guidance.

• Use reference lectures and additional resources for understanding the particle filter algorithm.

• Utilize the provided unit tests to validate your code by running unit_tests.py.

• Submit the modified files in the controller’s folder as instructed.

C. Instructions

Please follow these instructions carefully to ensure successful project completion. First, complete code modifications in geometry.py and environment.py:

o geometry.py: transform_point(), compose(), inverse()

o environment.py: read_marker_measures() and diff_drive_kinematics()

Run unit_test.py to verify your implementations in geometry.py and environment.py. Ensure all test cases pass before proceeding to the next steps. This step is crucial for validating the correctness of your code modifications. When the provided test cases in unit_tests.py pass, implement functions in particle_filter.py o particle_likelihood() o compute_particle_weights()

Your goal is to make the estimated robot pose as close as possible to the ground-truth robot pose.

You can open the world files in “worlds” folder and run the robot controller in Webots. The robot will move along a predefined trajectory. A Python GUI will display to visualize the particles. The larger triangles represent the robot and its estimation, and the smaller triangles indicate the particle poses. The orange and purple lines in front of the robot illustrate marker measurements by cameras and lidar, respectively, and the grey dashed lines are field-of-view of the robot. The small cyan dots represent the lidar array.

You can verify the particle filter convergence in one of the following ways:

o Test in Webots

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> Set DATA_CAPTURE_MODE = False in setting.py.

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> Open a Webots world file and run the attached controller.

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> A python GUI will show up to visualize the particles. o Capture data in Webots then run particle filters separately <img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> Set DATA_CAPTURE_MODE = True in setting.py.

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> Open a Webots world file and run the attached controller. The captured data will be stored in the “data” folder.

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> Change SCENARIO_NAME variable to the desired world name in run_pf.py.

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> Run run_pf.py in particle filter.

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> A python GUI will show up to visualize the particles.

It usually takes several minutes to finish running particle filter on the maps.

D. Hints for code completion:

• geometry.py:

o The SE2 class represents a 2D pose/transformation, incorporating both position and orientation components.

o Use this class to represent the pose of a coordinate frame, perform coordinate frame transformations, and apply transformation operations to rotate and translate coordinate frames or points.

o Implement methods for point transformation (transform_point), composition of transformations (compose), and inversion of transformations (inverse).

• environment.py:

o The read_marker_measures function generates expected ground-truth marker measurements given the pose of the robot.

o Utilize coordinate transformations to compute the marker positions relative to the robot’s pose. o Remember to handle visibility checks and consider hints provided in the function comments.

o Utilize the provided robot and wheel radius to convert wheel rotational speeds into linear and angular velocities for the diff_drive_kinematics function. And then, apply the kinematic equations specific to differential drive robots to calculate the forward speed and counterclockwise rotational speed based on the rotational speeds of the left and right wheels.

• particle_filter.py:

o The particle_likelihood function calculates the likelihood of a particle pose being the robot’s pose based on observed marker measurements.

o Treat unmatched particle marker measures as detection failures and unmatched robot marker measures as spurious detections.

o Utilize helper functions like generate_marker_pairs and marker_likelihood implemented in Project 3.

E. Submission:

F. Grading: (Total 100 points)

• Geometry.py (30 points) o transform_point () – 10 points o compose () – 10 points

o inverse () – 10 points

• environment.py (30 points) o read_marker_measures () – 20 points o diff_drive_odometry () – 10 points

• Integration test (40 points) o simple map – 15 points

o maze map – 25 points

G. Additional Notes:

• Run the provided local unit tests on the simple world before proceeding to the maze world.

• Ensure your implementations adhere to the specified requirements and maximize your score potential by following the instructions carefully.
