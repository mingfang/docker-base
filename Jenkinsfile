node {
   stage 'Checkout'
   checkout scm

   stage 'Build'
   sh "./build" 

   stage 'Push'
   sh "./push"   
}
