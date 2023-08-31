let time = () => {
  const date = new Date();
  const h = date.getHours();
  const hour = h % 12 || 12;
  const minute = date.getMinutes();
  const second = date.getSeconds();
  let digital = document.querySelector('.digital');
  digital.innerHTML = `${String(h).padStart(2, '0')}:${String(minute).padStart(2, '0')}:${String(second).padStart(2, '0')}`;
  document.getElementById('hour-hand').style.transform = `rotate(${hour * 30 + (0.5 * minute)}deg)`;
  
  document.getElementById('minute-hand').style.transform = `rotate(${minute * 6 + (0.1 * second)}deg)`;
  
  document.getElementById('second-hand').style.transform = `rotate(${second * 6}deg)`;
  
}
setInterval(time, 1000);
