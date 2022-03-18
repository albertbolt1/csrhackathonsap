# csrhackathonsap
<ul>
<li>The problem statement was to come up with measurements of a prosthetic by analysing the sizes of a given person(possible user of the prosthetic) by not touching them or taking measurements using a tape,the problem statement could be understood in multiple ways but we understood that we were supposed to take measurements from a long distance probably virtually</li>
  <li>There was a set of prosthetics which was specified to us in the PPT and all of them needed different measurments, some of them needed the measurements of feet,measurements from toe to head, some of them also needed us to calculate the size of the neck which changed the difficulty of the statement</li>
<li>me and my team were going through the ideas and we figured out that we didnt have enough data to train a model in the given time which will take in a set of pics and give the measurments of the prosthetic</li>
<li>we came across this idea of using mediapipe which can be used for computer vision tasks, its used for various purposes like face detection, posture detection and gesture detection etc</li>
<li>when we were going through the documentation of mediapipe we found out that mediapipe also gives us the 3d coordinates of the landmarks and we used these to come up with various measurments</li>
<li> we chose to give measurements for those prosthetics which could be calculated using the landmarks because the number of landmarks were limited</li>
<li> we had to decide which landmarks to use and then we just had to use a distance formulae to calculate the distance betweent the coordinates</li>
<li> I dont know how much it will be useful in the real world because the precision takes a big hit and no one would wanna wear a prosthetic which is loose or doesnot fit properly but we did give a dig at the problem to see what we could do and we found out that the measurements we calculated were pretty good for 4 to 5 people but I felt that there could be better methods to solve this problem</li>
<li> I am trying to find more accurate ways to estimate measurements of human body by using a image or video of the person</li>
</ul>
