pipeline{
    agent any

   stages{
     stage{

      Steps{
          sh 'javac -d . src/*.java'
          sh 'echo Main-Class: Rectangulator > MANIFEST.MF'
          sh 'jar -cvmf MANIFEST.MF rectangle.jar *.class'


      }
         }

   }


}