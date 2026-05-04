# asm\_lab6

laboratorio 6 en Dosbox

Checkpoint 1:
Se logro la compilacion, hubo correcion de errores debido a lineas de comentarios y/o decoracion las cuales no estaban bien comentadas, al arreglar este error, compilacion sin problemas.



Checkpoint 2:

Se observan los valores esperados, se logro hacer debug de manera correcta.



Checkpoint 3: Variante del Bucle (Factorial)



Modificación: Se reemplazó la instrucción ADD por MUL y se inicializó el acumulador AX en 1 para calcular el factorial de 5.  



Validación: La traza en DEBUG confirma la carga de datos iniciales; tras las 5 iteraciones del bucle, el registro AX alcanza el valor 0078h (120 decimal), cumpliendo con el resultado esperado.  



Conclusión Técnica: Se empleó la instrucción LOOP por ser más compacta, ya que decrementa CX y realiza el salto en un solo paso, mientras que la alternativa DEC/JNZ requiere dos instrucciones separadas para la misma lógica.

