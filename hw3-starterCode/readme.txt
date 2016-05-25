Assignment #3: Ray tracing

FULL NAME: Colin Cammarano


MANDATORY FEATURES
------------------

<Under "Status" please indicate whether it has been implemented and is
functioning correctly.  If not, please explain the current status.>

Feature:                                 Status: finish? (yes/no)
-------------------------------------    -------------------------
1) Ray tracing triangles                  yes

2) Ray tracing sphere                     yes

3) Triangle Phong Shading                 yes

4) Sphere Phong Shading                   yes

5) Shadows rays                           yes

6) Still images                           yes
   
7) Extra Credit (up to 20 points)
	Antialiasing:
		- Antialiasing was implemented using SSAA.
		- For every pixel, four rays are cast out from the camera, and the colors of the rays are averaged. This smooths some of the aliasing around the edges of the shapes and shadows.
		- To use, run homework 3 with three arguments: ./hw3 scene.scene out.jpg ssaa
