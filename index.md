<html><style>
.loader {  display: flex;  align-items: center;  justify-content: center;  flex-direction: row;}.slider {  overflow: hidden;  background-color: white;  margin: 0 15px;  height: 80px;  width: 20px;  border-radius: 30px;  box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.1), -15px -15px 30px #fff,    inset -5px -5px 10px rgba(0, 0, 255, 0.1),    inset 5px 5px 10px rgba(0, 0, 0, 0.1);  position: relative;}.slider::before {  content: "";  position: absolute;  top: 0;  left: 0;  height: 20px;  width: 20px;  border-radius: 100%;  box-shadow: inset 0px 0px 0px rgba(0, 0, 0, 0.3), 0px 420px 0 400px #2697f3,    inset 0px 0px 0px rgba(0, 0, 0, 0.1);  animation: animate_2 2.5s ease-in-out infinite;  animation-delay: calc(-0.5s * var(--i));}@keyframes animate_2 {  0% {    transform: translateY(250px);    filter: hue-rotate(0deg);  }  50% {    transform: translateY(0);  }  100% {    transform: translateY(250px);    filter: hue-rotate(180deg);  }}}
button {
  padding: 10px 20px;
  text-transform: uppercase;
  border-radius: 8px;
  font-size: 17px;
  font-weight: 500;
  color: #ffffff80;
  text-shadow: none;
  background: transparent;
  box-shadow: transparent;
  border: 1px solid #ffffff80;
  transition: 0.5s ease;
  user-select: none;
}#btn:hover,:focus {
  color: #ffffff;
  background: #008cff;
  border: 1px solid #008cff;
  text-shadow: 0 0 5px #ffffff,
              0 0 10px #ffffff,
              0 0 20px #ffffff;
  box-shadow: 0 0 5px #008cff,
              0 0 20px #008cff,
              0 0 50px #008cff,
              0 0 100px #008cff;
}
</style><body>  <section class="loader">    <div class="slider" style="--i:0">    </div>    <div class="slider" style="--i:1">    </div>    <div class="slider" style="--i:2">    </div>    <div class="slider" style="--i:3">    </div>    <div class="slider" style="--i:4">    </div>  </section><button>My Blog </button></body></html>