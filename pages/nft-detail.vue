<template>
    
        <!-- Start Hero -->
        <section class="relative table w-full md:pb-24 pb-16 mt-28">
            <div class="container">
                <div class="grid md:grid-cols-12 grid-cols-1 gap-[30px]">
                    <div class="lg:col-span-6 md:col-span-5">
                        <div class="sticky top-20">
                            <img src="@/assets/images/nft/items/item-detail-1.jpg" class="rounded-md shadow-md dark:shadow-gray-800" alt="">
                        </div>
                    </div><!--end col-->

                    <div class="lg:col-span-6 md:col-span-7">
                        <div class="">
                            <h5 class="lg:text-4xl lg:leading-relaxed text-2xl font-semibold">Wolf with Skull <span class="bg-gradient-to-r from-red-600 to-indigo-600 text-transparent bg-clip-text">Orange <br> Illustration</span> T-shirt Tattoo </h5>

                            <div class="grid md:grid-cols-2 grid-cols-1 mt-6">
                                <div>
                                    <h6 class="text-lg font-semibold">Current Bid:</h6>
                                    <h6 class="text-2xl font-semibold mt-2">4.85 ETH</h6>
                                    <h6 class="text-slate-400 mt-2">$450.48USD</h6>
                                </div>

                                <div>
                                    <h6 class="text-lg font-semibold">Auction Ending In:</h6>
                                    <span id="auction-item-1" class="text-2xl font-semibold mt-2"></span>
                                </div>
                            </div>

                            <div class="mt-6">
                                <a href="/" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md ltr:mr-2 rtl:ml-2"><i class="mdi mdi-gavel fs-5 ltr:mr-2 rtl:ml-2"></i> Place a Bid</a>
                                <a href="/" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md"><i class="mdi mdi-cart fs-5 ltr:mr-2 rtl:ml-2"></i> Buy Now</a>
                            </div>

                            <div class="grid grid-cols-1 mt-8">
                                <ul class="md:w-fit w-full flex-wrap justify-center text-center p-3 bg-white dark:bg-slate-900 shadow dark:shadow-gray-800 rounded-md" id="myTab" data-tabs-toggle="#StarterContent" role="tablist">
                                    <li role="presentation" class="md:inline-block block md:w-fit w-full">
                                        <button class="px-6 py-2 font-semibold rounded-md w-full hover:text-indigo-600 transition-all duration-500 ease-in-out" id="tuesday-tab" data-tabs-target="#tuesday" type="button" role="tab" aria-controls="tuesday" aria-selected="true">Details</button>
                                    </li>
                                    <li role="presentation" class="md:inline-block block md:w-fit w-full">
                                        <button class="px-6 py-2 font-semibold rounded-md w-full transition-all duration-500 ease-in-out" id="wednesday-tab" data-tabs-target="#wednesday" type="button" role="tab" aria-controls="wednesday" aria-selected="false">Bids</button>
                                    </li>
                                    <li role="presentation" class="md:inline-block block md:w-fit w-full">
                                        <button class="px-6 py-2 font-semibold rounded-md w-full transition-all duration-500 ease-in-out" id="thursday-tab" data-tabs-target="#thursday" type="button" role="tab" aria-controls="thursday" aria-selected="false">Activity</button>
                                    </li>
                                </ul>

                                <div id="StarterContent" class="mt-6">
                                    <div class="" id="tuesday" role="tabpanel" aria-labelledby="tuesday-tab">
                                        <div class="grid grid-cols-1">
                                            <p class="text-slate-400 mb-4">Hey guys! New exploration about NFT Marketplace Web Design, this time I'm inspired by one of my favorite NFT website called Superex (with crypto payment)! What do you think?</p>
                                            <p class="text-slate-400 mb-4">What does it mean? Biomechanics is the study of the structure, function and motion of the mechanical aspects of biological systems, at any level from whole organisms to organs, cells and cell organelles, using the methods of mechanics. Biomechanics is a branch of biophysics.</p>
                                            <h6 class="text-xl font-semibold">Owner</h6>
            
                                            <div class="flex items-center mt-3">
                                                <img src="@/assets/images/client/08.jpg" class="h-16 w-16 rounded-full shadow-md dark:shadow-gray-800" alt="">
                
                                                <div class="ltr:ml-3 rtl:mr-3">
                                                    <h6 class="text-lg font-semibold"><a href="/" class="hover:text-indigo-600 duration-500 ease-in-out">PandaOne</a></h6>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
            
                                    <div class="hidden" id="wednesday" role="tabpanel" aria-labelledby="wednesday-tab">
                                        <div class="grid grid-cols-1">
                                            <div class="flex items-center">
                                                <div class="relative">
                                                    <img src="@/assets/images/client/01.jpg" class="h-16 w-16 rounded-full shadow-md dark:shadow-gray-800" alt="">
                                                </div>
                
                                                <div class="ltr:ml-3 rtl:mr-3">
                                                    <h6 class="text-lg font-semibold">2 WETH <span class="text-slate-400">by</span> <a href="/" class="hover:text-indigo-600 duration-500 ease-in-out">0xe849fa28a...ea14</a></h6>
                                                    <span class="text-slate-400">6 hours ago</span>
                                                </div>
                                            </div>
            
                                            <div class="flex items-center mt-4">
                                                <div class="relative">
                                                    <img src="@/assets/images/client/02.jpg" class="h-16 w-16 rounded-full shadow-md dark:shadow-gray-800" alt="">
                                                </div>
                
                                                <div class="ltr:ml-3 rtl:mr-3">
                                                    <h6 class="text-lg font-semibold">0.001 WETH <span class="text-slate-400">by</span> <a href="/" class="hover:text-indigo-600 duration-500 ease-in-out">VOTwear</a></h6>
                                                    <span class="text-slate-400">6 hours ago</span>
                                                </div>
                                            </div>
            
                                            <div class="flex items-center mt-4">
                                                <div class="relative">
                                                    <img src="@/assets/images/client/03.jpg" class="h-16 w-16 rounded-full shadow-md dark:shadow-gray-800" alt="">
                                                </div>
                
                                                <div class="ltr:ml-3 rtl:mr-3">
                                                    <h6 class="text-lg font-semibold">1.225 WETH <span class="text-slate-400">by</span> <a href="/" class="hover:text-indigo-600 duration-500 ease-in-out">PandaOne</a></h6>
                                                    <span class="text-slate-400">6 hours ago</span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
            
                                    <div class="hidden" id="thursday" role="tabpanel" aria-labelledby="thursday-tab">
                                        <div class="grid grid-cols-1">
                                            <div class="rounded-md shadow dark:shadow-gray-800 p-6">
                                                <div class="flex items-center">
                                                    <div class="relative">
                                                        <img src="@/assets/images/nft/items/1.jpg" class="h-20 w-20 rounded-md shadow-md dark:shadow-gray-800" alt="">
        
                                                        <div class="absolute top-0 left-0 translate-middle px-1 rounded-md shadow-md bg-white">
                                                            <i class="mdi mdi-account-check mdi-18px text-green-600"></i>
                                                        </div>
                                                    </div>
                                                        
                                                    <span class="content ltr:ml-3 rtl:mr-3">
                                                        <a href="/" class="hover:text-indigo-600 text-lg block">Digital Art Collection</a>
                                                        <span class="text-slate-400 block mt-1">Started Following <a href="/" class="link font-semibold">@Panda</a></span>
                                                        
                                                        <span class="text-slate-400 block mt-1">1 hours ago</span>
                                                    </span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div><!--end col-->
                </div><!--end grid-->
            </div><!--end container-->

            <div class="container md:mt-24 mt-16">
                <div class="grid grid-cols-1 pb-8 text-center">
                    <h3 class="mb-6 md:text-3xl text-2xl md:leading-normal leading-normal font-semibold">Related Auction Items</h3>

                    <p class="text-slate-400 max-w-xl mx-auto">We are a huge marketplace dedicated to connecting great artists of all Techwind with their fans and unique token collectors!</p>
                </div><!--end grid-->

                <div class="grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 grid-cols-1 mt-8 gap-[30px]">
                    <!-- Start Bid -->
                    <div class="group relative overflow-hidden bg-white dark:bg-slate-900 rounded-md shadow dark:shadow-gray-800 hover:shadow-lg dark:hover:shadow-gray-800 duration-500 ease-in-out">
                        <div class="relative">
                            <img src="@/assets/images/nft/items/1.jpg" alt="">
                            <div class="absolute ltr:right-0 rtl:left-0 top-0 mt-6 ltr:mr-6 rtl:ml-6 opacity-0 group-hover:opacity-100 duration-500 ease-in-out">
                                <a href="/#!" class="btn btn-icon text-lg bg-white dark:bg-slate-900 border-0 shadow dark:shadow-gray-800 rounded-full text-red-600/20 hover:text-red-600 focus:text-red-600"><i class="mdi mdi-heart"></i></a>
                            </div>

                            <div class="absolute top-1/2 -translate-y-1/2 right-0 left-0 text-center opacity-0 group-hover:opacity-100 scale-0 group-hover:scale-100 duration-500 ease-in-out">
                                <a href="/nft-detail" class="btn btn-sm bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md">Place Bid</a>
                            </div>
                        </div>

                        <div class="p-6 relative">
                            <a href="/nft-detail" class="text-lg font-semibold hover:text-indigo-600 duration-500 ease-in-out">Deep Sea Phantasy</a>

                            <div class="flex items-center justify-between mt-2">
                                <div class="flex items-center">
                                    <i class="mdi mdi-ethereum text-xl leading-none text-indigo-600 ltr:mr-1 rtl:ml-1"></i>
                                    <span class="block font-semibold text-indigo-600">20.5 ETH</span>
                                </div>

                                <div>
                                    <i class="mdi mdi-heart text-red-600"></i> <span class="text-slate-400">22</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- End Bid -->
                    
                    <!-- Start Bid -->
                    <div class="group relative overflow-hidden bg-white dark:bg-slate-900 rounded-md shadow dark:shadow-gray-800 hover:shadow-lg dark:hover:shadow-gray-800 duration-500 ease-in-out">
                        <div class="relative">
                            <img src="@/assets/images/nft/items/2.jpg" alt="">
                            <div class="absolute ltr:right-0 rtl:left-0 top-0 mt-6 ltr:mr-6 rtl:ml-6 opacity-0 group-hover:opacity-100 duration-500 ease-in-out">
                                <a href="/#!" class="btn btn-icon text-lg bg-white dark:bg-slate-900 border-0 shadow dark:shadow-gray-800 rounded-full text-red-600/20 hover:text-red-600 focus:text-red-600"><i class="mdi mdi-heart"></i></a>
                            </div>

                            <div class="absolute top-1/2 -translate-y-1/2 right-0 left-0 text-center opacity-0 group-hover:opacity-100 scale-0 group-hover:scale-100 duration-500 ease-in-out">
                                <a href="/nft-detail" class="btn btn-sm bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md">Place Bid</a>
                            </div>
                        </div>

                        <div class="p-6 relative">
                            <a href="/nft-detail" class="text-lg font-semibold hover:text-indigo-600 duration-500 ease-in-out">CyberPrimal 042 LAN</a>

                            <div class="flex items-center justify-between mt-2">
                                <div class="flex items-center">
                                    <i class="mdi mdi-ethereum text-xl leading-none text-indigo-600 ltr:mr-1 rtl:ml-1"></i>
                                    <span class="block font-semibold text-indigo-600">20.5 ETH</span>
                                </div>

                                <div>
                                    <i class="mdi mdi-heart text-red-600"></i> <span class="text-slate-400">22</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- End Bid -->
                    
                    <!-- Start Bid -->
                    <div class="group relative overflow-hidden bg-white dark:bg-slate-900 rounded-md shadow dark:shadow-gray-800 hover:shadow-lg dark:hover:shadow-gray-800 duration-500 ease-in-out">
                        <div class="relative">
                            <img src="@/assets/images/nft/items/3.jpg" alt="">
                            <div class="absolute ltr:right-0 rtl:left-0 top-0 mt-6 ltr:mr-6 rtl:ml-6 opacity-0 group-hover:opacity-100 duration-500 ease-in-out">
                                <a href="/#!" class="btn btn-icon text-lg bg-white dark:bg-slate-900 border-0 shadow dark:shadow-gray-800 rounded-full text-red-600/20 hover:text-red-600 focus:text-red-600"><i class="mdi mdi-heart"></i></a>
                            </div>

                            <div class="absolute top-1/2 -translate-y-1/2 right-0 left-0 text-center opacity-0 group-hover:opacity-100 scale-0 group-hover:scale-100 duration-500 ease-in-out">
                                <a href="/nft-detail" class="btn btn-sm bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md">Place Bid</a>
                            </div>
                        </div>

                        <div class="p-6 relative">
                            <a href="/nft-detail" class="text-lg font-semibold hover:text-indigo-600 duration-500 ease-in-out">Crypto Egg Stamp #5</a>

                            <div class="flex items-center justify-between mt-2">
                                <div class="flex items-center">
                                    <i class="mdi mdi-ethereum text-xl leading-none text-indigo-600 ltr:mr-1 rtl:ml-1"></i>
                                    <span class="block font-semibold text-indigo-600">20.5 ETH</span>
                                </div>

                                <div>
                                    <i class="mdi mdi-heart text-red-600"></i> <span class="text-slate-400">22</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- End Bid -->
                    
                    <!-- Start Bid -->
                    <div class="group relative overflow-hidden bg-white dark:bg-slate-900 rounded-md shadow dark:shadow-gray-800 hover:shadow-lg dark:hover:shadow-gray-800 duration-500 ease-in-out">
                        <div class="relative">
                            <img src="@/assets/images/nft/items/4.jpg" alt="">
                            <div class="absolute ltr:right-0 rtl:left-0 top-0 mt-6 ltr:mr-6 rtl:ml-6 opacity-0 group-hover:opacity-100 duration-500 ease-in-out">
                                <a href="/#!" class="btn btn-icon text-lg bg-white dark:bg-slate-900 border-0 shadow dark:shadow-gray-800 rounded-full text-red-600/20 hover:text-red-600 focus:text-red-600"><i class="mdi mdi-heart"></i></a>
                            </div>

                            <div class="absolute top-1/2 -translate-y-1/2 right-0 left-0 text-center opacity-0 group-hover:opacity-100 scale-0 group-hover:scale-100 duration-500 ease-in-out">
                                <a href="/nft-detail" class="btn btn-sm bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md">Place Bid</a>
                            </div>
                        </div>

                        <div class="p-6 relative">
                            <a href="/nft-detail" class="text-lg font-semibold hover:text-indigo-600 duration-500 ease-in-out">Color Abstract Painting</a>

                            <div class="flex items-center justify-between mt-2">
                                <div class="flex items-center">
                                    <i class="mdi mdi-ethereum text-xl leading-none text-indigo-600 ltr:mr-1 rtl:ml-1"></i>
                                    <span class="block font-semibold text-indigo-600">20.5 ETH</span>
                                </div>

                                <div>
                                    <i class="mdi mdi-heart text-red-600"></i> <span class="text-slate-400">22</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- End Bid -->
                </div>
            </div>
        </section><!--end end section-->
        <!-- End -->
</template>