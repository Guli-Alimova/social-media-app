<script setup>
import { FireIcon, ChevronDownIcon, HomeIcon, UsersIcon, ChatIcon, BellIcon, CogIcon, SearchIcon  } from '@heroicons/vue/outline'

</script>

<template>
    <div class="px-6 py-6 bg-white">
        <div class="container flex items-center justify-between mx-auto max-x-screen-2xl">
            <div class="flex items-center space-x-3">
                <span><FireIcon class="w-10 h-10 text-blue-500" /></span>
                <div class="relative"> 
                    <span class="absolute ml-4 transform translate-y-4 "><SearchIcon class="w-5 h-5 text-gray-400"/></span>
                    <input class="w-64 py-2 border-2 rounded-full outline-none pl-11 focus:border-blue-500" type="text" placeholder="Search">
                </div>
               
            </div>
            <ul class="flex items-center space-x-8">
                <li class="flex items-center space-x-3 cursor-pointer">
                    <span><HomeIcon class="w-6 h-6 text-blue-500"/></span>
                    <span>Homepage</span>
                </li>
                <li class="flex items-center space-x-3 cursor-pointer">
                    <span><UsersIcon class="w-6 h-6 text-blue-500"/></span>
                    <span>Connections</span>
                </li>
                <li class="flex items-center space-x-3 cursor-pointer">
                    <span><ChatIcon class="w-6 h-6 text-blue-500"/></span>
                    <span>Messages</span>
                </li>
                <li class="flex items-center space-x-3 cursor-pointer">
                    <span><BellIcon class="w-6 h-6 text-blue-500"/></span>
                    <span>Notification</span>
                </li>
                <li class="flex items-center space-x-3 cursor-pointer">
                    <span><CogIcon class="w-6 h-6 text-blue-500"/></span>
                    <span>Tools</span>
                </li>
            </ul>
            <div class="flex items-center space-x-3 cursor-pointer">
                <div class="w-8 h-8 overflow-hidden rounded-full">
                    <img class="object-cover w-full h-auto" src="../assets/img/alexander-hipp-iEEBWgY_6lA-unsplash.jpg" alt="avatar">
                </div>
                <span>Ersad Basbag</span>
                <div><ChevronDownIcon class="w-4 h-4"/></div>
            </div>
            
        </div>

    </div>
</template>
