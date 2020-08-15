# run_analysis
Primero se nombraron los diferentes datasets y se colocaron nombres que permitieran diferenciar sus respectivas columnas.

Se realizaron dos dataframes (X y Y) de los datos de train y test, también se realizó un dataframe (Sujeto) de los datos obtenidos de los sujetos tanto de train como test, posteriormente los dos dataframes resultantes se unieron en un nuevo dataframe llamado (Datos_Juntos).

Se creó un dataframe (Datos_organizados) en el cual se seleccionaron columnas especificas de los datos de (Datos_Juntos) a las cuales se especificó que se añadiera el promedio y la desviación estándar, posteriormente se extrajó el "code" para poder añadir las actividades respectivas.

Se renombró cada actividad, para mejorar la referencia de actividades y finalmente al conjunto de Datos_organizados se le agrupó por sujeto y actividad y se le nombró (FinalData)
