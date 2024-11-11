- 👋 Hi, I’m @YordanDobrev
- 👀 I’m interested in Software and Hardware
- 🌱 I’m currently learning Python DB module in Softuni.
- I am interested in crypto industry and AI.
- I have experience as MIS Technician, Data Analyst, Business Analyst, Business Process Analyst and Process Engineer.
<p align="center">
<img
src='https://github.com/YordanDobrev/GIF/assets/145679398/0bff60cb-0638-4df5-8c15-897e3806d7bb'
width="170" height="170"/>
</p>
/**
  * pong
  *
  * @author jh3y - jheytompkins.com
*/
.pong {
  background: repeating-linear-gradient(180deg, var(--primary) 0, var(--primary) 4%, transparent 4%, transparent 6%, var(--primary) 6%) 49px 0/2px 100% no-repeat;
  height: 100px;
  position: absolute;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
  width: 100px; }
  .pong div {
    content: -850 741, 850 812, -850 -615, 850 437, -850 655, 850 -117, -850 -345, 850 -515, -850 -55, 850 562, -850 556, 850 819, -850 590, 850 384, -850 -854, 850 -27, -850 215, 850 921, -850 13, 850 -79, -850 213, 850 -602, -850 -763, 850 -660; }
    .pong div:nth-child(1) {
      -webkit-animation: play 6s infinite linear alternate;
              animation: play 6s infinite linear alternate;
      background: var(--primary);
      height: 5%;
      left: 50%;
      position: absolute;
      top: 50%;
      width: 5%;
      will-change: transform;
      z-index: 2;
      content: -850 741; }
    .pong div:nth-child(2), .pong div:nth-child(3) {
      -webkit-animation-direction: alternate;
              animation-direction: alternate;
      -webkit-animation-duration: 6s;
              animation-duration: 6s;
      -webkit-animation-iteration-count: infinite;
              animation-iteration-count: infinite;
      -webkit-animation-timing-function: linear;
              animation-timing-function: linear;
      background: var(--primary);
      height: 15%;
      position: absolute;
      top: 50%;
      width: 5%;
      will-change: transform; }
    .pong div:nth-child(2) {
      -webkit-animation-name: moveOne;
              animation-name: moveOne;
      left: 0; }
    .pong div:nth-child(3) {
      -webkit-animation-name: moveTwo;
              animation-name: moveTwo;
      right: 0; }

@-webkit-keyframes play {
  0% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, 741%);
            transform: translate(-50%, -50%) translate(-850%, 741%); }
  10% {
    -webkit-transform: translate(-50%, -50%) translate(850%, 812%);
            transform: translate(-50%, -50%) translate(850%, 812%); }
  20% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, -615%);
            transform: translate(-50%, -50%) translate(-850%, -615%); }
  30% {
    -webkit-transform: translate(-50%, -50%) translate(850%, 437%);
            transform: translate(-50%, -50%) translate(850%, 437%); }
  40% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, 655%);
            transform: translate(-50%, -50%) translate(-850%, 655%); }
  50% {
    -webkit-transform: translate(-50%, -50%) translate(850%, -117%);
            transform: translate(-50%, -50%) translate(850%, -117%); }
  60% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, -345%);
            transform: translate(-50%, -50%) translate(-850%, -345%); }
  70% {
    -webkit-transform: translate(-50%, -50%) translate(850%, -515%);
            transform: translate(-50%, -50%) translate(850%, -515%); }
  80% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, -55%);
            transform: translate(-50%, -50%) translate(-850%, -55%); }
  90% {
    -webkit-transform: translate(-50%, -50%) translate(850%, 562%);
            transform: translate(-50%, -50%) translate(850%, 562%); }
  100% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, 741%);
            transform: translate(-50%, -50%) translate(-850%, 741%); } }

@keyframes play {
  0% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, 741%);
            transform: translate(-50%, -50%) translate(-850%, 741%); }
  10% {
    -webkit-transform: translate(-50%, -50%) translate(850%, 812%);
            transform: translate(-50%, -50%) translate(850%, 812%); }
  20% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, -615%);
            transform: translate(-50%, -50%) translate(-850%, -615%); }
  30% {
    -webkit-transform: translate(-50%, -50%) translate(850%, 437%);
            transform: translate(-50%, -50%) translate(850%, 437%); }
  40% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, 655%);
            transform: translate(-50%, -50%) translate(-850%, 655%); }
  50% {
    -webkit-transform: translate(-50%, -50%) translate(850%, -117%);
            transform: translate(-50%, -50%) translate(850%, -117%); }
  60% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, -345%);
            transform: translate(-50%, -50%) translate(-850%, -345%); }
  70% {
    -webkit-transform: translate(-50%, -50%) translate(850%, -515%);
            transform: translate(-50%, -50%) translate(850%, -515%); }
  80% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, -55%);
            transform: translate(-50%, -50%) translate(-850%, -55%); }
  90% {
    -webkit-transform: translate(-50%, -50%) translate(850%, 562%);
            transform: translate(-50%, -50%) translate(850%, 562%); }
  100% {
    -webkit-transform: translate(-50%, -50%) translate(-850%, 741%);
            transform: translate(-50%, -50%) translate(-850%, 741%); } }

@-webkit-keyframes moveOne {
  0% {
    -webkit-transform: translate(0%, -50%) translate(0%, 247%);
            transform: translate(0%, -50%) translate(0%, 247%); }
  20%, 30% {
    -webkit-transform: translate(0%, -50%) translate(0%, -205%);
            transform: translate(0%, -50%) translate(0%, -205%); }
  40%, 50% {
    -webkit-transform: translate(0%, -50%) translate(0%, 218.33333%);
            transform: translate(0%, -50%) translate(0%, 218.33333%); }
  60%, 70% {
    -webkit-transform: translate(0%, -50%) translate(0%, -115%);
            transform: translate(0%, -50%) translate(0%, -115%); }
  80%, 90% {
    -webkit-transform: translate(0%, -50%) translate(0%, -18.33333%);
            transform: translate(0%, -50%) translate(0%, -18.33333%); }
  100% {
    -webkit-transform: translate(0%, -50%) translate(0%, 247%);
            transform: translate(0%, -50%) translate(0%, 247%); } }

@keyframes moveOne {
  0% {
    -webkit-transform: translate(0%, -50%) translate(0%, 247%);
            transform: translate(0%, -50%) translate(0%, 247%); }
  20%, 30% {
    -webkit-transform: translate(0%, -50%) translate(0%, -205%);
            transform: translate(0%, -50%) translate(0%, -205%); }
  40%, 50% {
    -webkit-transform: translate(0%, -50%) translate(0%, 218.33333%);
            transform: translate(0%, -50%) translate(0%, 218.33333%); }
  60%, 70% {
    -webkit-transform: translate(0%, -50%) translate(0%, -115%);
            transform: translate(0%, -50%) translate(0%, -115%); }
  80%, 90% {
    -webkit-transform: translate(0%, -50%) translate(0%, -18.33333%);
            transform: translate(0%, -50%) translate(0%, -18.33333%); }
  100% {
    -webkit-transform: translate(0%, -50%) translate(0%, 247%);
            transform: translate(0%, -50%) translate(0%, 247%); } }

@-webkit-keyframes moveTwo {
  0% {
    content: 850 812;
    -webkit-transform: translate(0%, -50%) translate(0%, 270.66667%);
            transform: translate(0%, -50%) translate(0%, 270.66667%); }
  20%, 10% {
    -webkit-transform: translate(0%, -50%) translate(0%, 270.66667%);
            transform: translate(0%, -50%) translate(0%, 270.66667%); }
  40%, 30% {
    -webkit-transform: translate(0%, -50%) translate(0%, 145.66667%);
            transform: translate(0%, -50%) translate(0%, 145.66667%); }
  60%, 50% {
    -webkit-transform: translate(0%, -50%) translate(0%, -39%);
            transform: translate(0%, -50%) translate(0%, -39%); }
  80%, 70% {
    -webkit-transform: translate(0%, -50%) translate(0%, -171.66667%);
            transform: translate(0%, -50%) translate(0%, -171.66667%); }
  100%, 90% {
    -webkit-transform: translate(0%, -50%) translate(0%, 187.33333%);
            transform: translate(0%, -50%) translate(0%, 187.33333%); } }

@keyframes moveTwo {
  0% {
    content: 850 812;
    -webkit-transform: translate(0%, -50%) translate(0%, 270.66667%);
            transform: translate(0%, -50%) translate(0%, 270.66667%); }
  20%, 10% {
    -webkit-transform: translate(0%, -50%) translate(0%, 270.66667%);
            transform: translate(0%, -50%) translate(0%, 270.66667%); }
  40%, 30% {
    -webkit-transform: translate(0%, -50%) translate(0%, 145.66667%);
            transform: translate(0%, -50%) translate(0%, 145.66667%); }
  60%, 50% {
    -webkit-transform: translate(0%, -50%) translate(0%, -39%);
            transform: translate(0%, -50%) translate(0%, -39%); }
  80%, 70% {
    -webkit-transform: translate(0%, -50%) translate(0%, -171.66667%);
            transform: translate(0%, -50%) translate(0%, -171.66667%); }
  100%, 90% {
    -webkit-transform: translate(0%, -50%) translate(0%, 187.33333%);
            transform: translate(0%, -50%) translate(0%, 187.33333%); } }