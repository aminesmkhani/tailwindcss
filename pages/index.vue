<template>
    <div class="text-gray-900 text-sm">
        <nav class="bg-gray-900 text-white px-4 py-3 flex items-center justify-between">
          <div class="flex items-center space-x-4">
            <a href="#" class="text-white hover:text-gray-400">
              <svg class="w-8 fill-current" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
            </a>
            <div class="relative">
              <input type="text" class="rounded bg-gray-700 placeholder-white w-72 px-3 py-1" placeholder="Search or jump to...">
              <div class="absolute top-0 right-0 flex items-center h-full">
                <div class="border border-gray-600 rounded text-xs text-gray-400 px-2 mr-2">/</div>
              </div>
            </div>
            <ul class="flex item-center font-semibold space-x-4">
              <li><a href="" class="hover:text-gray-400">Pull Request</a></li>
              <li><a href="" class="hover:text-gray-400">Issues</a></li>
              <li><a href="" class="hover:text-gray-400">Marketplace</a></li>
              <li><a href="" class="hover:text-gray-400">Explore</a></li>
            </ul>
          </div>
          <div class="flex items-center space-x-4 text-white">
            <a href="#" class="relative hover:text-gray-400" >
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path></svg>
              <div class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0"></div>
            </a>
            <a href="#" class="flex items-center hover:text-gray-400" >
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"></path></svg>
              <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
            </a>
            <a href="#" class="flex items-center hover:text-gray-400" >
              <img alt="@aminesmkhani" width="20" height="20" src="https://avatars.githubusercontent.com/u/34412105?s=60&amp;v=4" class="w-5 h-5 rounded-full">
              <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
            </a>
          </div>
        </nav>
      <div class="repo-stats flex items-center justify-between px-8 py-4">
          <div class="flex">
            <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16"   aria-hidden="true"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"></path></svg>
            <div class="flex items-center text-xl ml-2">
              <a href="" class="text-blue-600 hover:underline">aminesmkhani</a>
              <span class="ml-1 text-blue-600">/</span>
              <a href="" class="text-blue-600 hover:underline font-semibold ml-1">tailwindcss</a>
            </div>
          </div>
        <div class="flex space-x-2">
          <div class="flex text-xs">
              <button class="border border-gray-400 rounded rounded-r-none px-3 py-1 flex items-center space-x-1">
                <svg class="text-gray-600 w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"></path></svg>
                <div>Watch</div>
                <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
              </button>
              <a href="#" class="border border-gray-400 rounded rounded-l-none border-l-0 font-semibold hover:text-blue-600 px-3 py-1">430</a>
          </div>
          <div class="flex text-xs">
              <button class="border border-gray-400 rounded rounded-r-none px-3 py-1 flex items-center space-x-1">
                <svg class="w-4 fill-current text-gray-600"  viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"></path></svg>
                <div>Star</div>
                <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
              </button>
              <a href="#" class="border border-gray-400 rounded rounded-l-none border-l-0 font-semibold hover:text-blue-600 px-3 py-1">430</a>
          </div>
          <div class="flex text-xs">
              <button class="border border-gray-400 rounded rounded-r-none px-3 py-1 flex items-center space-x-1">
                <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16"  aria-hidden="true"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"></path></svg>
                <div>Fork</div>
                <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
              </button>
              <a href="#" class="border border-gray-400 rounded rounded-l-none border-l-0 font-semibold hover:text-blue-600 px-3 py-1">1.2k</a>
          </div>
        </div>
      </div><!--End Repo states-->
      <ul class="repo-nav border-b border-gray-400 flex items-center px-8 mt-4">
        <li class="font-semibold">
          <a href="#" class="flex items-center border-b-2 border-red-500 px-4 pb-3">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
            <span class="ml-2">Code</span>
          </a>
        </li>
        <li>
        <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
          <svg class="w-4 fill-current text-gray-600"  viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"></path></svg>
          <span class="ml-2">Issues</span>
          <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">33</div>
        </a>
      </li>
        <li>
          <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
            <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16"  aria-hidden="true"><path fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"></path></svg>
            <span class="ml-2">Pull Requests</span>
            <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">39</div>
          </a>
        </li>
        <li>
          <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
            <svg class="w-4 fill-current text-gray-600"  viewBox="0 0 16 16"  aria-hidden="true"><path fill-rule="evenodd" d="M1.5 2.75a.25.25 0 01.25-.25h8.5a.25.25 0 01.25.25v5.5a.25.25 0 01-.25.25h-3.5a.75.75 0 00-.53.22L3.5 11.44V9.25a.75.75 0 00-.75-.75h-1a.25.25 0 01-.25-.25v-5.5zM1.75 1A1.75 1.75 0 000 2.75v5.5C0 9.216.784 10 1.75 10H2v1.543a1.457 1.457 0 002.487 1.03L7.061 10h3.189A1.75 1.75 0 0012 8.25v-5.5A1.75 1.75 0 0010.25 1h-8.5zM14.5 4.75a.25.25 0 00-.25-.25h-.5a.75.75 0 110-1.5h.5c.966 0 1.75.784 1.75 1.75v5.5A1.75 1.75 0 0114.25 12H14v1.543a1.457 1.457 0 01-2.487 1.03L9.22 12.28a.75.75 0 111.06-1.06l2.22 2.22v-2.19a.75.75 0 01.75-.75h1a.25.25 0 00.25-.25v-5.5z"></path></svg>
            <span class="ml-2">Discussions</span>
          </a>
        </li>
        <li>
          <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
            <svg class="w-4 fill-current text-gray-600"  viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"></path></svg>
            <span class="ml-2">Action</span>
          </a>
        </li>
        <li>
          <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
            <svg class="w-4 fill-current text-gray-600"  viewBox="0 0 16 16"  aria-hidden="true"><path fill-rule="evenodd" d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"></path></svg>
            <span class="ml-2">Security</span>
          </a>
        </li>
        <li>
          <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
            <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16"  aria-hidden="true"><path fill-rule="evenodd" d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"></path></svg>
            <span class="ml-2">Insights</span>
          </a>
        </li>
      </ul> <!-- End Repo Nav -->
      <div class="container mx-auto my-8 px-4 flex flex-col lg:flex-row">
        <div class="file-explorer-container w-full lg:w-3/4 lg:mr-8">
          <div class="branch-navigation flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <button class="border border-gray-400 rounded-md px-4 py-1 hover:bg-gray-200 flex items-center space-x-2">
                <svg class="fill-current text-gray-600 w-4" text="gray" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path></svg>
                <div class="font-semibold">master</div>
                <svg class="w-3 ml-1" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M19 9l-7 7-7-7"></path></svg>
              </button>
              <a href="#" class="hidden lg:flex items-center space-x-2 py-1 group">
                <svg class="fill-current text-gray-600 group-hover:text-blue-600 w-4" text="gray" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path></svg>
                <span class="group-hover:text-blue-600">
                <span class="font-semibold">25 </span>
                <span class="text-gray-600">branches</span>
              </span>
              </a>
              <a href="#" class="hidden py-1 lg:flex items-center space-x-2 group">
                <svg class="fill-current text-gray-600 group-hover:text-blue-600 w-4" text="gray" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"></path></svg>
                <span class="text-gray-700 group-hover:text-blue-600">
                <span class="font-semibold">79</span>
                <span class="text-gray-600">tags</span>
              </span>
              </a>
            </div>
            <div class="hidden lg:flex items-center space-x-2">
              <button class="border border-gray-400 rounded-md px-3 py-1 hover:bg-gray-200 flex items-center space-x-2">
                <div class="font-semibold">Go to file</div>
              </button>
              <button class="border border-gray-400 rounded-md px-3 py-1 hover:bg-gray-200 flex items-center space-x-1">
                <div class="font-semibold">Add file</div>
                <svg class="w-4" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
              </button>
              <button class="font-semibold border border-gray-400 rounded-md text-white bg-green-600 hover:bg-green-700 px-4 py-1 flex items-center space-x-2">
                <svg class="w-4 fill-current text-gray-200" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.47 10.78a.75.75 0 001.06 0l3.75-3.75a.75.75 0 00-1.06-1.06L8.75 8.44V1.75a.75.75 0 00-1.5 0v6.69L4.78 5.97a.75.75 0 00-1.06 1.06l3.75 3.75zM3.75 13a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5z"></path></svg>
                <div>Code</div>
                <svg class="w-3 ml-1" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M19 9l-7 7-7-7"></path></svg>
              </button>
            </div>
          </div> <!-- End Branch-Navigation -->

            <div class="commits-container bg-blue-100 rounded-md rounded-b-none border border-blue-200 border-b-0 flex items-center justify-between px-4 py-4 mt-5">
                <div class="flex items-center space-x-2">

                  <a href="#" class="font-semibold hover:underline">adamwathan</a>
                  <a href="#" class="hover:underline hover:text-blue-600">2.0.2</a>
                </div>
                <div>two</div>
            </div><!-- End Commits Container -->

          </div><!-- End File-explorer-container -->
        <div class="sidebar w-1/4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aperiam at atque, autem commodi cum deserunt ducimus, et ex facere facilis inventore ipsam laudantium maiores modi necessitatibus neque porro, qui quia repudiandae sunt tenetur voluptatum. A asperiores aspernatur atque beatae blanditiis consequatur dolor dolorem dolorum ea eius error ex facilis fugiat harum ipsa iure iusto magni maxime necessitatibus nemo nesciunt officia perferendis perspiciatis quia quisquam ratione repellat repudiandae rerum saepe sint soluta sunt tempore, vitae! Aperiam fugiat harum inventore pariatur reiciendis. A autem error esse eveniet ex fugit maxime numquam pariatur porro quas quis repellendus repudiandae sint, sit suscipit voluptatum?
        </div><!-- End SideBar -->
      </div>

    </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
