<template>
  <footer id="contact">
    <div
      class="mx-auto max-w-screen-xl space-y-6 px-4 py-16 sm:px-6 lg:space-y-16 lg:px-6"
    >
      <div class="grid grid-cols-1 gap-6 lg:grid-cols-3">
        <div>
          <div class="flex items-center">
            <img
              width="48"
              height="48"
              class="rounded-md overflow-hidden mr-6"
              src="/logo.png"
              alt="earth-worm-logo"
            />
            <span class="text-3xl mt-4">Earthworm</span>
          </div>

          <p class="mt-4 max-w-[16rem] text-base leading-relaxed typing">
            一起来加入我们
            <span
              class="bg-clip-text text-transparent bg-gradient-to-r from-purple-400 via-purple-400 to-gray-400 dark:from-purple-600 dark:to-gray-100"
              >Earthworm</span
            >!
          </p>

          <ul class="mt-8 flex gap-6">
            <li>
              <a
                href="https://twitter.com/cui_xiaorui"
                rel="noreferrer"
                target="_blank"
                class="transition hover:opacity-75"
              >
                <span class="sr-only">Twitter</span>

                <svg
                  class="h-6 w-6 hover:text-[#03a9f4]"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                  aria-hidden="true"
                >
                  <path
                    d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
                  />
                </svg>
              </a>
            </li>

            <li>
              <a
                href="https://github.com/cuixueshe/earthworm"
                rel="noreferrer"
                target="_blank"
                class="transition hover:opacity-75"
              >
                <span class="sr-only">GitHub</span>

                <svg
                  class="h-6 w-6 hover:text-gray-600"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                    clip-rule="evenodd"
                  />
                </svg>
              </a>
            </li>
          </ul>
        </div>

        <div
          class="grid grid-cols-1 gap-6 sm:grid-cols-2 lg:col-span-2 lg:grid-cols-4"
        >
          <div>
            <p class="font-medium text-lg">Earthworm</p>

            <ul class="mt-6 space-y-4 text-sm">
              <li>
                <a
                  href="https://github.com/cuixueshe/earthworm"
                  class="transition hover:opacity-75"
                >
                  Open Source
                </a>
              </li>

              <li>
                <a
                  href="https://github.com/cuixueshe/earthworm/issues"
                  class="transition hover:opacity-75"
                >
                  Issues
                </a>
              </li>

              <li>
                <a
                  href="https://github.com/cuixueshe/earthworm/issues/91"
                  class="transition hover:opacity-75"
                >
                  贡献代码
                </a>
              </li>
            </ul>
          </div>

          <div>
            <p class="font-medium text-lg">团队</p>

            <ul class="mt-6 space-y-4 text-sm">
              <li>
                <a
                  href="https://t.me/+dohhXSz-5n1kZDQ1"
                  class="transition hover:opacity-75"
                >
                  联系我们
                </a>
              </li>

              <!-- <li>
                <a
                  href="#faq"
                  class="transition hover:opacity-75"
                >
                  常见问题
                </a>
              </li> -->
            </ul>
          </div>

          <!-- <div>
            <p class="font-medium text-lg">教学</p>

            <ul class="mt-6 space-y-4 text-sm">
              <li>
                <a
                  href="https://github.com/cuixueshe/earthworm"
                  class="transition hover:opacity-75"
                >
                  关于我们
                </a>
              </li>
            </ul>
          </div> -->
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts"></script>

<style scoped>
@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

@keyframes blink-cursor {
  from,
  to {
    border-color: transparent;
  }
  50% {
    border-color: rgba(228, 110, 255, 0.75);
  }
}

.typing {
  overflow: hidden;
  border-right: 0.25em solid rgba(228, 110, 255, 0.75);
  white-space: nowrap;
  letter-spacing: 0.15em;
  animation:
    typing 3.5s steps(40, end),
    blink-cursor 0.75s step-end infinite;
}
</style>
