<template>
  <div class="h-screen flex flex-col">
    <header class="flex flex-shrink-0">
      <!--  Left Side  -->
      <div class="w-64 flex-shrink-0 px-4 py-3 bg-gray-800">
        <button class="block w-full flex items-center">
          <img class="h-8 w-8 rounded-full object-cover"
               src="https://images.unsplash.com/photo-1639628735078-ed2f038a193e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=6&w=144&q=80"
               alt="">
          <span class="ml-4 mr-2 text-sm font-medium text-white">John Deo</span>
          <svg class="ml-auto w-6 h-6 fill-current text-gray-400" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
                d="M17 9.17a1 1 0 0 0-1.41 0L12 12.71 8.46 9.17a1 1 0 1 0-1.41 1.42l4.24 4.24a1.001 1.001 0 0 0 1.42 0L17 10.59a.999.999 0 0 0 0-1.42Z"/>
          </svg>
        </button>
      </div>

      <!--  Left Side  -->
      <div class="flex-1 flex items-center justify-between px-6 bg-gray-700">
        <nav class="flex">
          <a href="#" class="inline-block px-3 py-2 bg-gray-800 rounded-lg leading-none text-sm font-medium text-white">Mailbox</a>
          <a href="#"
             class="ml-2 inline-block px-3 py-2 rounded-lg leading-none text-sm font-medium text-white hover:bg-gray-600">Customers</a>
          <a href="#"
             class="ml-2 inline-block px-3 py-2 rounded-lg leading-none text-sm font-medium text-white hover:bg-gray-600">Reporting</a>
          <a href="#"
             class="ml-2 inline-block px-3 py-2 rounded-lg leading-none text-sm font-medium text-white hover:bg-gray-600">Manage</a>
        </nav>
        <div class="flex items-center">
          <div class="relative w-56">
          <span class="absolute flex items-center inset-y-0 left-0 pl-2">
            <svg class="h-5 w-5 text-gray-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                 stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round"
                    d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607z"/>
            </svg>
          </span>
            <input
                class="block pl-9 px-4 py-2 w-full bg-gray-900 rounded-lg text-sm placeholder-gray-400 text-white focus:bg-white focus:text-gray-900 focus:placeholder-gray-600 focus:outline-none"
                placeholder="Search">
          </div>
          <button class="ml-6 text-gray-400 hover:text-gray-200">
            <svg class="h-6 w-6 fill-current" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path
                  d="M18 13.18V10a6 6 0 0 0-5-5.91V3a1 1 0 0 0-2 0v1.09A6 6 0 0 0 6 10v3.18A3 3 0 0 0 4 16v2a1 1 0 0 0 1 1h3.14a4 4 0 0 0 7.72 0H19a1 1 0 0 0 1-1v-2a3 3 0 0 0-2-2.82ZM8 10a4 4 0 0 1 8 0v3H8v-3Zm4 10a2 2 0 0 1-1.72-1h3.44A2 2 0 0 1 12 20Zm6-3H6v-1a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v1Z"/>
            </svg>
          </button>
          <button class="ml-4 text-gray-400 hover:text-gray-200">
            <svg class="h-6 w-6 fill-current" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path
                  d="M11.29 15.29a1.573 1.573 0 0 0-.12.15.762.762 0 0 0-.09.18.643.643 0 0 0-.06.18 1.362 1.362 0 0 0 0 .2.84.84 0 0 0 .08.38.9.9 0 0 0 .54.54.94.94 0 0 0 .76 0 .9.9 0 0 0 .54-.54A1 1 0 0 0 13 16a1 1 0 0 0-1.71-.71ZM12 2a10 10 0 1 0 0 20 10 10 0 0 0 0-20Zm0 18a8 8 0 1 1 0-16.001A8 8 0 0 1 12 20Zm0-13a3 3 0 0 0-2.6 1.5 1 1 0 1 0 1.73 1A1 1 0 0 1 12 9a1 1 0 1 1 0 2 1 1 0 0 0-1 1v1a1 1 0 0 0 2 0v-.18A3 3 0 0 0 12 7Z"/>
            </svg>
          </button>
        </div>
      </div>
    </header>
    <div class="flex-1 flex bg-gray-200 overflow-hidden">
      <div class="w-64 p-6 bg-gray-100">
        <nav>
          <h2 class="text-xs font-semibold text-gray-600 uppercase tracking-wide">Mailboxes</h2>
          <div class="mt-3">
            <a href="#!"
               class="mt-3 -mx-4 py-2 px-4 flex items-center justify-between text-sm font-medium bg-gray-200 rounded-lg">
            <span class="inline-flex">
              <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                      d="M20 13V6a2 2 0 00-2-2H6a2 2 0 00-2 2v7m16 0v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-5m16 0h-2.586a1 1 0 00-.707.293l-2.414 2.414a1 1 0 01-.707.293h-3.172a1 1 0 01-.707-.293l-2.414-2.414A1 1 0 006.586 13H4"></path>
              </svg>
              <span class="ml-2 text-gray-900">Inbox</span>
            </span>
              <span
                  class="inline-block w-9 text-center py-1 leading-none text-xs font-semibold text-gray-700 bg-gray-300 rounded-full">6</span>
            </a>

            <a href="#!"
               class="mt-3 -mx-4 py-2 px-4 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
            <span class="inline-flex">
              <svg class="w-6 h-6 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round"
                      stroke-width="2"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"></path></svg>
              <span class="ml-2 text-gray-900">Flagged</span>
            </span>
            </a>

            <a href="#!"
               class="mt-3 -mx-4 py-2 px-4 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
            <span class="inline-flex">
              <svg class="w-6 h-6 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                      d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"></path>
              </svg>
              <span class="ml-2 text-gray-900">Draft</span>
            </span>
              <span
                  class="inline-block w-9 text-center py-1 leading-none text-xs font-semibold text-gray-700 bg-gray-300 rounded-full">6</span>
            </a>

            <a href="#!"
               class="mt-3 -mx-4 py-2 px-4 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
            <span class="inline-flex">
              <svg class="w-6 h-6 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                      d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
              <span class="ml-2 text-gray-900">Assigned</span>
            </span>
              <span
                  class="inline-block w-9 text-center py-1 leading-none text-xs font-semibold text-gray-700 bg-gray-300 rounded-full">6</span>
            </a>

            <a href="#!"
               class="mt-3 -mx-4 py-2 px-4 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
              <span class="inline-flex">
                <svg class="w-6 h-6 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                     xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
                <span class="ml-2 text-gray-900">Closed</span>
              </span>
            </a>

            <a href="#!"
               class="mt-3 -mx-4 py-2 px-4 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
              <span class="inline-flex">
                <svg class="w-6 h-6 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                     stroke-width="1.5"
                     stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round"
                          d="M20.25 7.5l-.625 10.632a2.25 2.25 0 01-2.247 2.118H6.622a2.25 2.25 0 01-2.247-2.118L3.75 7.5M10 11.25h4M3.375 7.5h17.25c.621 0 1.125-.504 1.125-1.125v-1.5c0-.621-.504-1.125-1.125-1.125H3.375c-.621 0-1.125.504-1.125 1.125v1.5c0 .621.504 1.125 1.125 1.125z"/>
                </svg>

                <span class="ml-2 text-gray-900">Junk</span>
              </span>
            </a>
          </div>
          <h2 class="mt-8 text-xs font-semibold text-gray-600 uppercase tracking-wide">Folders</h2>
          <div class="mt-4">
            <a href="#!" class="mt-4 block text-xs font-medium text-gray-700">Refunds</a>
            <a href="#!" class="mt-4 block text-xs font-medium text-gray-700">Discounts</a>
            <a href="#!" class="mt-4 block text-xs font-medium text-gray-700">Bugs</a>
          </div>
        </nav>
      </div>
      <main class="flex-1 flex">
        <div class="flex flex-col w-full max-w-xs flex-grow border-l border-r">
          <div class="flex-shrink-0 px-4 py-2 flex items-center justify-between border-b">
            <button class="flex items-center text-sm font-semibold text-gray-600">
              Short by data
              <svg class="ml-1 w-6 h-6 fill-current text-gray-500" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M17 9.17a1 1 0 0 0-1.41 0L12 12.71 8.46 9.17a1 1 0 1 0-1.41 1.42l4.24 4.24a1.001 1.001 0 0 0 1.42 0L17 10.59a.999.999 0 0 0 0-1.42Z"/>
              </svg>
            </button>
            <button>
              <svg class="w-6 h-6 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 4.5h14.25M3 9h9.75M3 13.5h5.25m5.25-.75L17.25 9m0 0L21 12.75M17.25 9v12" />
              </svg>

            </button>
          </div>
          <div class="flex-1 overflow-y-auto">
            <a href="#" class="block px-6 pt-3 pb-4 bg-white">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">
                  Asmit Nepali
                </span>
                <span class="text-sm text-gray-600">
                  2 days ago
                </span>
              </div>
              <p class="text-xs text-gray-900">Refund</p>
              <p class="text-xs mt-2 text-gray-600">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </a>
          </div>
        </div>
        <div class="flex-1">
          <div>
            <div class="flex px-5 py-4 items-center justify-between bg-gray-100">
              <div class="flex items-center">
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16l-4-4m0 0l4-4m-4 4h18"></path>
                </svg>
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 7h.01M7 3h5c.512 0 1.024.195 1.414.586l7 7a2 2 0 010 2.828l-7 7a2 2 0 01-2.828 0l-7-7A1.994 1.994 0 013 12V7a4 4 0 014-4z"></path>
                </svg>
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                     xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3M3 17V7a2 2 0 012-2h6l2 2h6a2 2 0 012 2v8a2 2 0 01-2 2H5a2 2 0 01-2-2z"></path>
                </svg>
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z"></path>
                </svg>
              </div>
              <div class="flex items-center">
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                </svg>
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 15l7-7 7 7"></path>
                </svg>
              </div>
            </div>
            <div></div>
          </div>
          <div>
            <article></article>
            <article></article>
            <article></article>
          </div>
        </div>
      </main>
    </div>
  </div>
</template>