
### 1. Mobil robot

#### A. Playground Robot

- [Gazebo install](https://gazebosim.org/docs/harmonic/install_ubuntu)
- [Setting up a robot simulation (Gazebo)](https://docs.ros.org/en/humble/Tutorials/Advanced/Simulators/Gazebo/Gazebo.html)

![playground_robot.png](https://abc-irobotics.github.io/advanced_ros_course_materials_hu/img/playground_robot.png)

#### B. TurtleBot4

- [TurtleBot4 Simulator Tutorial](https://turtlebot.github.io/turtlebot4-user-manual/software/turtlebot4_simulator.html)
- [TurtleBot4 GUI Docs](https://turtlebot.github.io/turtlebot4-user-manual/software/turtlebot4_common.html#menu-control)

![turtlebot.png](https://abc-irobotics.github.io/advanced_ros_course_materials_hu/img/turtlebot.png)

#### C. PlatypOUs (ROS 1)

- [PlatypOUs GitHub](https://github.com/ABC-iRobotics/PlatypOUs-Mobile-Robot-Platform)

![](https://www.mdpi.com/sensors/sensors-22-02284/article_deploy/html/images/sensors-22-02284-g001.png)

#### D. Bármilyen mobil robot

---

#### 1.1. Mobil robot akadály elkerülés

- **Basic:** Szimulátor élesztése. ROS node/node-ok implementálása szenzorok adatainak beolvasására és a a robot mozgatására.
- **Advanced:** ROS rendszer implementálása akadály felismerésére és az akadályt kikerülő trajektória tervezésére és megvalósítására szimulált környezetben bármely szenzor felhasználásával.
- **Epic:** Nyűgözz le!

---

#### 1.2. Mobil robot pályakövetés

- **Basic:** Szimulátor élesztése. ROS node/node-ok implementálása szenzorok adatainak beolvasására és a a robot mozgatására.
- **Advanced:** ROS rendszer implementálása pályakövetésre szimulált környezetben bármely szenzor felhasználásával(pl. fal mellett haladás adott távolságra LIDAR segítségével).
- **Epic:** Nyűgözz le!

---

#### 1.3. Mobil robot objektum követés/visual servoing

- **Basic:** Szimulátor élesztése. ROS node/node-ok implementálása szenzorok adatainak beolvasására és a a robot mozgatására.
- **Advanced:** ROS rendszer implementálása objektum megkeresésére/felismerésére és követésére/megközelítésére szimulált környezetben bármely szenzor felhasználásával (pl. visual servoing).
- **Epic:** Nyűgözz le!

---

#### 1.4. Mobil robot action library

- **Basic:** Szimulátor élesztése. ROS node/node-ok implementálása szenzorok adatainak beolvasására és a a robot mozgatására.
- **Advanced:** Egyszerű műveleteket tartalmazó, ROS action alapú könyvtár és ezeket végrehajtó rendszer implementálása (pl. push object, move to object, turn around).
- **Epic:** Nyűgözz le!

---

### 2. Quadcopter

- [Gazebo install](https://gazebosim.org/docs/harmonic/install_ubuntu)
- [Setting up a robot simulation (Gazebo)](https://docs.ros.org/en/humble/Tutorials/Advanced/Simulators/Gazebo/Gazebo.html)
    
    `ign gazebo -v 4 -r quadcopter.sdf`
    

![quadcopter.png](https://abc-irobotics.github.io/advanced_ros_course_materials_hu/img/quadcopter.png)

- **Basic:** Szimulátor élesztése. ROS node/node-ok implementálása szenzorok adatainak beolvasására és a a robot mozgatására.
- **Advanced:** ROS rendszer implementálása magasság/sebesség szabályozására.
- **Epic:** Nyűgözz le!

---

### 3. Szabadon választott Gazebo szimuláció

- [Gazebo install](https://gazebosim.org/docs/harmonic/install_ubuntu)
- [Setting up a robot simulation (Gazebo)](https://docs.ros.org/en/humble/Tutorials/Advanced/Simulators/Gazebo/Gazebo.html)
- [Gazebo World Examples](https://github.com/gazebosim/gz-sim/tree/gz-sim7/examples/worlds)

![pendulum.png](https://abc-irobotics.github.io/advanced_ros_course_materials_hu/img/pendulum.png)

Megegyezés alapján.

---

### 4. Gazebo szimuláció összeállítása

- [Gazebo install](https://gazebosim.org/docs/harmonic/install_ubuntu)
- [Setting up a robot simulation (Gazebo)](https://docs.ros.org/en/humble/Tutorials/Advanced/Simulators/Gazebo/Gazebo.html)
- [Gazebo World Examples](https://github.com/gazebosim/gz-sim/tree/gz-sim7/examples/worlds)

![velocity.png](https://abc-irobotics.github.io/advanced_ros_course_materials_hu/img/velocity.png)

Megegyezés alapján.

---

### 5. TurtleSim

- [Turtlesim Tutorial](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Introducing-Turtlesim/Introducing-Turtlesim.html)
- [Koch Görbe](https://en.wikipedia.org/wiki/Koch_snowflake)

![turtle_xmas_fast.gif](https://abc-irobotics.github.io/advanced_ros_course_materials_hu/img/turtle_xmas_fast.gif)

#### 5.1 Turtlesim Fraktál/Szöveg

- **Basic:** Arányos szabályozó implementálása.
- **Advanced:** Fraktál/szöveg rajzolása.
- **Epic:** Nyűgözz le!

---

### 6. DVRK

- [Download and compile dVRK 2](https://github.com/jhu-dvrk/sawIntuitiveResearchKit/wiki/BuildROS2)
- [Marker examples](https://www.programcreek.com/python/example/88812/visualization_msgs.msg.Marker)

![PSM_coordinates.png](https://abc-irobotics.github.io/advanced_ros_course_materials_hu/img/PSM_coordinates.png)

#### 6.1 DVRK Interaktív Marker

Megfogható, mozgatható marker implementálása a DVRK szimulátorához.

---

### 7. YouBot (Windows)

- [YouBot controller GitHub](https://github.com/ABC-iRobotics/YoubotDriver/tree/ROS)

---

#### 7.1. YouBot ROS integráció

- **Basic:** YouBot repo build-elése, megismerése
- **Advanced:** Szimulált robot mozgatása csuklótérben ROS környezetben
- **Epic:** Tesztelés valós roboton és/vagy nyűgözz le!

---

### X. Saját téma

---

Megegyezés alapján.


[[Kötelező program leírás|vissza]]