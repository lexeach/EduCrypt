# How to Update When New Webiste is Updated:

#  Changes in Course English File
    1- First Add  loader on Hearder part
            <link rel="stylesheet" href="./loader.css" type="text/css">
    2- Add Overlay page and import web3 and blockchain on top after body start
                   <div class="loader-overlay">
                   <div class="loader"></div>
                   </div>

               <script src="https://cdn.jsdelivr.net/npm/web3/dist/web3.min.js"></script>
                <script src="./Blockchain/blockchain.js"></script>

# Syllabus English:
    1- import web.js and courseEnglish file at 
              <script src="https://cdn.jsdelivr.net/npm/web3/dist/web3.min.js"></script>
              <script src="./Blockchain/courseEnglish.js"></script>
    2- Change Div where Connect Wallet is found inside section replace with given below div
              <div class="align-center container">
                <div class="row justify-content-center">
                    <div class="col-12 col-lg-8">
                        <button id="connectWallet" class="btn btn-primary display-4">Connect Wallet</button>
                    </div>
                </div>
            </div>

    3-  add id to this div 
                  <div class="align-center container">
                           <div class="row justify-content-center">
                                     <div class="col-12 col-lg-8">
                                               <div  id="courseButtonContainerEnglish"  class="mbr-section-btn"><a class="btn btn-white display-4" >Buy
                                                   Course</a></div>
                                                     </div>
                                                    </div>
                                 </div>


#  Syllabus Hindi
  1- import web.js and courseEnglish file at 
              <script src="https://cdn.jsdelivr.net/npm/web3/dist/web3.min.js"></script>
              <script src="./Blockchain/courseEnglish.js"></script>
2- Update connect wallet div with given below div
              <div class="navbar-buttons mbr-section-btn">
                            <button id="connectWallet1" class="btn btn-primary display-4">Connect Wallet</button>
                        </div>
3-  add id to this div 
                  <div class="align-center container">
                           <div class="row justify-content-center">
                                     <div class="col-12 col-lg-8">
                                               <div  id="courseButtonContainerHindi"  class="mbr-section-btn"><a class="btn btn-white display-4" >Buy
                                                   Course</a></div>
                                                     </div>
                                                    </div>
                                 </div>

                            

#  Changes in Course Hindi File
    1- First Add  loader on Hearder part
            <link rel="stylesheet" href="./loader.css" type="text/css">

    2- Add Overlay page and import web3 and blockchain on top after body start
                   <div class="loader-overlay">
                   <div class="loader"></div>
                   </div>
               <script src="https://cdn.jsdelivr.net/npm/web3/dist/web3.min.js"></script>
                <script src="./Blockchain/blockchain.js"></script>