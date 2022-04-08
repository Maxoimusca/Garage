# Garage
function Car(props) {   return &lt;li>I am a { props.brand }&lt;/li>; }  function Garage() {   const cars = ['Ford', 'BMW', 'Audi'];   return (     &lt;>       &lt;h1>Who lives in my garage?&lt;/h1>       &lt;ul>         {cars.map((car) => &lt;Car brand={car} />)}       &lt;/ul>     &lt;/>   ); }  ReactDOM.render(&lt;Garage />, document.getElementById('root'));
