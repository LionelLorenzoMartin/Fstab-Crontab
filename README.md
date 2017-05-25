# Fstab




<img src="https://github.com/LionelLorenzoMartin/Fstab-Crontab/blob/master/photo_2017-05-25_16-36-34.jpg" />




# Ejercicios cron.  
- Programar un trabajo (A) para ejecutarse en el minuto 30 de cada hora de cada día.
30 * * * * root echo A >> /etc/trabajos
date >> /etc/trabajos

- Programar un trabajo (B) para ejecutarse cada día a las 20:30h.
30 20 * * * root echo B >> /etc/trabajos
date >> /etc/trabajos

- Programar un trabajo (C) para ejecutarse de lunes a viernes a las 20:30h.
30 20 * * 1-5 root echo C >> /etc/trabajos
date >> /etc/trabajos

- Programar un trabajo (D) para ejecutarse los martes y los jueves a las 20:30h.
30 * * * 2,4 root echo D >> /etc/trabajos
date >> /etc/trabajos

- Programar un trabajo (E) para ejecutarse los días 10 y 20 de todos los meses a las 20:30h.
30 * * * * root echo E >> /etc/trabajos
date >> /etc/trabajos

- Programar un trabajo (F) para ejecutarse cada 15 minutos.
15,30,45,0 * * * * root echo F >> /etc/trabajos
date >> /etc/trabajos

- Programar un trabajo (G) para ejecutarse cada día a las 00:00h.
0 0 * * * root echo G >> /etc/trabajos
date >> /etc/trabajos

- Programar un trabajo (H) para ejecutarse cada primer día de mes a las 00:00h.  
0 0 1 * * root echo H >> /etc/trabajos
date >> /etc/trabajos
