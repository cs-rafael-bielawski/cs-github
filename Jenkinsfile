stage 'Checkout'
 node('master') {
   deleteDir()
     checkout scm
      }

stage 'Code Pull'
 node ('master') {
   gitpull scm
 	  }
