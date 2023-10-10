# Taller 3
- Creo la rama primera en el repositorio ejemploramas de forma local y compruebo que se ha creado la rama.
  
  `git branch primera`
  
  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/ea6d273c-2457-415c-81d1-460e42373e4a)
 
  `git branch`
  
  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/33bb7c68-06df-4c9a-abc1-032065da3be1)

  
- Me muevo a la rama primera, creo el archivo y luego lo fusiono con la rama principal.

  `git checkout primera`
  
  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/7496666f-3411-43f1-aeac-17b2b21a7c9c)

  `touch fichero`
  
  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/1f0e5dc4-337a-47f3-a64a-72e1a7cad425)

  `git checkout main`

  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/bed28e78-bff0-4cdf-8ea9-e12fe8f17839)

  `git merge primera`

  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/9e0f94ee-5a1d-4031-a190-97b6f1d278d6)

  En este caso no ha habido ningun conflicto al fusionar las ramas ya que el archivo solo estaba creado en la rama primera.

- Creo la rama segunda y provoco un conficto al fusionar con main para generar el conflicto en el archivo primero cambio      algo de la misma linea.
  
  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/91a88573-6cc4-4cb3-9da5-0a3fd54f7331)

  No me ha dejado fusionar por que he generado un conflicto en la misma linea.
  Al ejecutar `nano fichero` nos saldran las dos versiones 
  
  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/10eb8ba2-10e5-4a6b-a304-fc858510ec1a)

  Aqui elegimos como queremos dejar el archivo y salimos guardando.
  Despues ejecutaremos `git add .` y `git commit`.
  
  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/7a554fbb-026f-4bed-a4ba-03cc853363a3)

- Sincronizo con el repositorio remoto y compruebo que esta la rama.

  ![image](https://github.com/ManuFdzDC/prueba_manuelfernandez/assets/144890528/d1ef81c5-b053-4088-bd45-4c17b01b5d5f)

  



  


