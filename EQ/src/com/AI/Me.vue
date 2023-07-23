<template>
    <!-- align-items-center -->
    <div class="row">
        <div class="col-6 col-md-3">
            <img class="shadow-lg p-3 mb-5 bg-body-tertiary rounded" src="/images/dog.jpeg" width="200" />
        </div>

        <div class="col-sm-6 col-md-9 ">
            <div class="container mb-4 ">
                <div class="row align-items-start ">
                    <div class="col-5 ">
                        <h3>Sackdyxay keomorlakoth</h3>
                    </div>
                    <div class="col d-flex opacity-50">
                        <span class="material-symbols-outlined ">
                            location_on
                        </span>&nbsp;
                        vientiane
                    </div>
                    <div class="col d-flex opacity-50">
                        <span class="material-symbols-outlined">
                            bookmark
                        </span>&nbsp;
                        Bookmark   
                    </div>
                    <h6 style="color: blue;">Product designer</h6>
                </div>
            </div>

            <div class="container row align-items-center mb-4">
                <div>RANKING</div>
                <div class="container row align-items-center d-flex">
                    <h3>8,6
                        <span class="material-symbols-outlined" style="color: blue;">
                            star
                        </span><span class="material-symbols-outlined" style="color: blue;">
                            star
                        </span><span class="material-symbols-outlined" style="color: blue;">
                            star
                        </span><span class="material-symbols-outlined" style="color: blue;">
                            star
                        </span><span class="material-symbols-outlined" style="color:slategray;">
                            star
                        </span>
                    </h3>
                </div>
            </div>

            <div class="container row align-items-center mb-5">
                <div class="row">
                    <div class="col d-flex">
                        <span class="material-symbols-outlined">
                            chat_bubble
                        </span>&nbsp;
                        Send message
                    </div>
                    <div class="col d-flex" style="background-color: rgb(179, 225, 248); ">
                        <div>
                            <span class="material-symbols-outlined" style="color: blue;">
                                check
                            </span>
                        </div>&nbsp;
                        <div style="color: blue;">Contacts</div>
                    </div>
                    <div class="col d-flex opacity-50">
                        <span class="material-symbols-outlined">
                            report
                        </span>&nbsp;
                        Report user
                    </div>
                </div>
            </div>

            <div class="container text-center">
                <div class="row row-cols-auto">
                    <div class="col d-flex opacity-50">
                        <span class="material-symbols-outlined">
                            visibility
                        </span> &nbsp;
                        Timeline
                    </div>
                    <div class="col d-flex">
                        <span class="material-symbols-outlined">
                            person
                        </span>&nbsp; 
                        About
                    </div>
                </div>
            </div>
        </div>
    </div>
    <Skill />
</template>

<script setup>
import Skill from '../Skill.vue';
</script>