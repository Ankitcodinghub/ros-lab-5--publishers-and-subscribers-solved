# ros-lab-5--publishers-and-subscribers-solved
**TO GET THIS SOLUTION VISIT:** [ROS Lab 5- Publishers and Subscribers Solved](https://www.ankitcodinghub.com/product/ros-lab-5-publishers-and-subscribers-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94518&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ROS Lab 5- Publishers and Subscribers Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Task 1: Mouse Tracker

<ol>
<li>a) &nbsp;In this laboratory exercise, we will upgrade the mouse tracker package and use it to navigate the trutlebot from the turtlesim package. First, run track mouse.launch file created in the previous exercise and list the published topics. Copy the obtained list and paste it in the text box.</li>
<li>b) &nbsp;Write a ROS node, turtle control.py, that will control the position of the first turtle in order to follow the mouse. You need to control both the angle and the distance towards the mouse. Make sure to use classes. Two following code snippets might help you get going.
def getdistance(self, goalx, goaly):

distance = sqrt(pow((goal x − self .pose.x), 2)

+ pow((goal y − self.pose.y), 2)) return distance
</li>
</ol>
def get ang distance(self , goal x , goal y):

ang distance = atan2(goal pose.y − self .pose.y, goal pose.x − self.pose.x) − self.pose.theta return ang distance

Keep in mind the difference between the screen coordinate system, with the origin in the top left corner of the monitor, and the turtlesim coordinate system, with the origin in the bottom left corner of the turtlesim window. You should also address the difference between you screen resolution and the turtlesim screen resolution (the turtle should follow the relative position of the mouse on your screen, i.e. it should not hit the wall if you did not reach the edge of your screen).

c) Add your node to the track mouse.launch file and expose the screen resolution as ROS parameter using &lt;param&gt; tag. You are not allowed to use hard coded screen resolution within the turtle control.py node.

Exercise submission

Create a zip archive containing this pdf file with the filled out answers and the mouse tracker package. Upload the archive to Moodle.

</div>
</div>
<div class="layoutArea">
<div class="column">
Laboratory exercise 5, ROS: Publishers and Subscribers 1

</div>
</div>
</div>
