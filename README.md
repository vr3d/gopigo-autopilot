<h1>GoPiGo: Self-driving car</h1>

<p align="center">
  <img src="img/GoPiGo.jpg"/>
</p>

[comment]: <> (Needs a companion CSS file to format Two cols)

<table>
  <tbody>
    <tr>
      <th>Hardware</th>
      <th>Software Dependencies</th>
    </tr>
    <tr>
      <td>
        <ul>
          <li><a href="https://aws.amazon.com/ec2/instance-types/p2/">AWS EC2 P2 instance</a> - (1) NVIDIA K80 GPU </li>
          <li><a href="https://www.apple.com/macos/sierra/">macOS Sierra</a> - (1) Intel Iris Graphics 1600 GPU </li>
          <li><a href="https://www.dexterindustries.com/GoPiGo/">Dexters Industries GoPiGo</a></li>
            <ul>
              <li>Raspberry Pi 3</li>
              <li>Picamera</li>
              <li>Ultrasonic sensor</li>
        </ul>
      <td>
        <ul>
          <li>Bitfusion Ubuntu 14 Tensorflow - Ubuntu 14.04 LTS:
            <ul>
              <li><a href="https://www.digitalocean.com/community/tutorials/how-to-install-the-anaconda-python-distribution-on-ubuntu-16-04">Anaconda 4.3</a> : Python 3.5 env</li>
              <li>Numpy 1.12</li>
              <li>TensorFlow 1.0 + Keras 2.0</li>
              <li><a href="http://opencv.org/">OpenCV</a> 3.1</li>
              <li><a href="https://www.pygame.org/docs/)">Pygame</a> 1.9</li>
              <li><a href="https://pypi.python.org/pypi/pyserial">PySerial</a> 3.3</li>
            </ul>
          <li>macOS:
            <ul>
              <li><a href="https://www.continuum.io/anaconda-overview">Anaconda 4.3</a> : Python 3.5 env</li>
              <li>Numpy 1.12</li>
              <li>TensorFlow 1.0 + Keras 2.0</li>
              <li><a href="http://opencv.org/">OpenCV</a> 3.1</li>
              <li><a href="https://www.pygame.org/docs/)">Pygame</a> 1.9</li>
              <li><a href="https://pypi.python.org/pypi/pyserial">PySerial</a> 3.3</li>
            </ul>
          <li>Raspberry Pi:
            <ul>
              <li>GoPiGo Python modules</li>
              <li><a href="http://picamera.readthedocs.io/en/release-1.13/">Picamera</a></li>
              <li>VIM editor :: for quick writing/refactoring</li>
            </ul>
         </ul>
      </td>
    </tr>
  </tbody>
</table>
