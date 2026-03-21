<script setup></script>

<template>
  <nav
    class="bg-neutral-primary fixed w-full z-20 top-0 start-0 border-b border-default"
  >
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <a
        href="https://flowbite.com/"
        class="flex items-center space-x-3 rtl:space-x-reverse"
      >
        <img
          src="https://flowbite.com/docs/images/logo.svg"
          class="h-7"
          alt="Flowbite Logo"
        />
        <span
          class="self-center text-xl text-heading font-semibold whitespace-nowrap"
          >Flowbite</span
        >
      </a>
      <div class="flex md:order-2 space-x-3 md:space-x-0 rtl:space-x-reverse">
        <button
          type="button"
          class="text-white bg-brand hover:bg-brand-strong box-border border border-transparent focus:ring-4 focus:ring-brand-medium shadow-xs font-medium leading-5 rounded-base text-sm px-3 py-2 focus:outline-none"
        >
          Get started
        </button>
        <button
          data-collapse-toggle="navbar-sticky"
          type="button"
          class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-body rounded-base md:hidden hover:bg-neutral-secondary-soft hover:text-heading focus:outline-none focus:ring-2 focus:ring-neutral-tertiary"
          aria-controls="navbar-sticky"
          aria-expanded="false"
        >
          <span class="sr-only">Open main menu</span>
          <svg
            class="w-6 h-6"
            aria-hidden="true"
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            fill="none"
            viewBox="0 0 24 24"
          >
            <path
              stroke="currentColor"
              stroke-linecap="round"
              stroke-width="2"
              d="M5 7h14M5 12h14M5 17h14"
            />
          </svg>
        </button>
      </div>
      <div
        class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
        id="navbar-sticky"
      >
        <ul
          class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-default rounded-base bg-neutral-secondary-soft md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0 md:bg-neutral-primary"
        >
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-white bg-brand rounded-sm md:bg-transparent md:text-fg-brand md:p-0"
              aria-current="page"
              >Home</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-heading rounded hover:bg-neutral-tertiary md:hover:bg-transparent md:border-0 md:hover:text-fg-brand md:p-0 md:dark:hover:bg-transparent"
              >About</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-heading rounded hover:bg-neutral-tertiary md:hover:bg-transparent md:border-0 md:hover:text-fg-brand md:p-0 md:dark:hover:bg-transparent"
              >Services</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-heading rounded hover:bg-neutral-tertiary md:hover:bg-transparent md:border-0 md:hover:text-fg-brand md:p-0 md:dark:hover:bg-transparent"
              >Contact</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="bg-white dark:bg-gray-900">
    <div
      class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12"
    >
      <div class="mr-auto place-self-center lg:col-span-7">
        <h1
          class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white"
        >
          Payments tool for software companies
        </h1>
        <p
          class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400"
        >
          From checkout to global sales tax compliance, companies around the
          world use Flowbite to simplify their payment stack.
        </p>
        <a
          href="#"
          class="inline-flex items-center justify-center px-5 py-3 mr-3 text-base font-medium text-center text-white rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900"
        >
          Get started
          <svg
            class="w-5 h-5 ml-2 -mr-1"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </a>
        <a
          href="#"
          class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800"
        >
          Speak to Sales
        </a>
      </div>
      <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
        <img
          src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/hero/phone-mockup.png"
          alt="mockup"
        />
      </div>
    </div>
  </section>
</template>
