# guia_yii2
Esta guía contendrá todo el material necesario para la instalación desde cero  de este fabuloso Framework
Links con informacion importante para el aprendizaje
http://www.freetuts.org/tutorial/view?id=6#theming (temas)
http://www.yiiframework.com/doc-2.0/ guia
http://tutsplus.com/tutorials/search?utf8=%E2%9C%93&search%5Btopic%5D=&search%5Bterms%5D=Yii2
https://packagist.org/packages/ repositorios composer
http://www.yiiframework.com/extension/

CONEXION A BASE DE DATOS POSTGRES
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'pgsql:host=localhost;dbname=db_name', 
    'username' => 'db_username',
    'password' => 'db_password',
    'charset' => 'utf8',
    'schemaMap' => [
      'pgsql'=> [
        'class'=>'yii\db\pgsql\Schema',
        'defaultSchema' => 'public' //specify your schema here
      ]
    ], // PostgreSQL
];

guia practica de git 

https://github.com/kuryaki/LearningGitHub/blob/master/README.md

