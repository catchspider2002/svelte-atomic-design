<script>
  import Card from "./Molecules/MoleculeCard.svelte";
  import Progress from "./Molecules/MoleculeProgress.svelte";
  import Pricing from "./Molecules/MoleculePricing.svelte";
  import Button from "./Molecules/Atoms/AtomButton.svelte";
</script>

<div class="bg-gray-200">
  <nav class="flex items-center justify-between flex-wrap bg-teal-500 p-6">
    <div class="flex items-center flex-shrink-0 text-white mr-6">
      <svg
        class="fill-current h-8 w-8 mr-2"
        width="54"
        height="54"
        viewBox="0 0 54 54"
        xmlns="http://www.w3.org/2000/svg">
        <path
          d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45
          3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8
          0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2
          6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45
          9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8
          0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z" />
      </svg>
      <span class="font-semibold text-xl tracking-tight">Tailwind CSS</span>
    </div>
    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-teal-200
        border-teal-400 hover:text-white hover:border-white">
        <svg
          class="fill-current h-3 w-3"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg">
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
      <div class="text-sm lg:flex-grow">
        <a
          href="#responsive-header"
          class="block mt-4 lg:inline-block lg:mt-0 text-teal-200
          hover:text-white mr-4">
          Docs
        </a>
        <a
          href="#responsive-header"
          class="block mt-4 lg:inline-block lg:mt-0 text-teal-200
          hover:text-white mr-4">
          Examples
        </a>
        <a
          href="#responsive-header"
          class="block mt-4 lg:inline-block lg:mt-0 text-teal-200
          hover:text-white">
          Blog
        </a>
      </div>
      <div>
        <a
          href="#"
          class="inline-block text-sm px-4 py-2 leading-none border rounded
          text-white border-white hover:border-transparent hover:text-teal-500
          hover:bg-white mt-4 lg:mt-0">
          Download
        </a>
      </div>
    </div>
  </nav>

  <span class="title">Svelte App</span>
  <p />
  <Progress label="WordPress" value="90" />
  <Progress label="CSS" value="40" />
  <p />
  <p />
  <Pricing title="" val1="" val2="" val3="" val4="" val5="" val6="" />
  <p />
  <p />
  <Card title="New title" subtitle="Sub" />
  <p class="m-8" />
  <button class="hvr-sweep-to-right">Test button</button>
  <Button text="Button" className="bg-blue-500 hover:bg-blue-700 text-white" />
  <button
    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4
    rounded-full">
    Button
  </button>
  <button
    class="bg-transparent hover:bg-blue-500 text-blue-700 font-semibold
    hover:text-white py-2 px-4 border border-blue-500 hover:border-transparent
    rounded">
    Button
  </button>
  <Button
    text="BUtton"
    className="bg-blue-500 hover:bg-blue-700 text-white border border-blue-700 " />
  <Button
    text="Button"
    className="bg-blue-500 hover:bg-blue-400 text-white border-b-4 border-blue-700
    hover:border-blue-500" />
  <div class="inline-flex">
    <button
      class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4
      rounded-l">
      Prev
    </button>
    <button
      class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4
      rounded-r">
      Next
    </button>
  </div>
  <button
    class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4
    rounded inline-flex items-center">
    <svg
      class="fill-current w-4 h-4 mr-2"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 20 20">
      <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
    </svg>
    <span>Download</span>
  </button>
  <button
    class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4
    rounded inline-flex items-center">
    <span>Download</span>
    <svg
      class="fill-current w-4 h-4 ml-2"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 20 20">
      <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
    </svg>
  </button>
  <button
    class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4
    rounded inline-flex items-center hvr-icon-bounce">
    <svg
      class="hvr-icon fill-current w-4 h-4 mr-2"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 20 20">
      <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
    </svg>
    <span>Download</span>
  </button>
</div>

<p class="m-8" />

<div class="w-full max-w-xs">
  <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
    <div class="mb-4">
      <label class="block text-gray-700 text-sm font-bold mb-2" for="username">
        Username
      </label>
      <input
        class="shadow appearance-none border rounded w-full py-2 px-3
        text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
        id="username"
        type="text"
        placeholder="Username" />
    </div>
    <div class="mb-6">
      <label class="block text-gray-700 text-sm font-bold mb-2" for="password">
        Password
      </label>
      <input
        class="shadow appearance-none border border-red-500 rounded w-full py-2
        px-3 text-gray-700 mb-3 leading-tight focus:outline-none
        focus:shadow-outline"
        id="password"
        type="password"
        placeholder="******************" />
      <p class="text-red-500 text-xs italic">Please choose a password.</p>
    </div>
    <div class="flex items-center justify-between">
      <button
        class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4
        rounded focus:outline-none focus:shadow-outline"
        type="button">
        Sign In
      </button>
      <a
        class="inline-block align-baseline font-bold text-sm text-blue-500
        hover:text-blue-800"
        href="#">
        Forgot Password?
      </a>
    </div>
  </form>
  <p class="text-center text-gray-500 text-xs">
    &copy;2019 Acme Corp. All rights reserved.
  </p>
</div>

<p class="m-8" />
<form class="w-full max-w-sm">
  <div class="md:flex md:items-center mb-6">
    <div class="md:w-1/3">
      <label
        class="block text-gray-500 font-bold md:text-right mb-1 md:mb-0 pr-4"
        for="inline-full-name">
        Full Name
      </label>
    </div>
    <div class="md:w-2/3">
      <input
        class="bg-gray-200 appearance-none border-2 border-gray-200 rounded
        w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none
        focus:bg-white focus:border-purple-500"
        id="inline-full-name"
        type="text"
        value="Jane Doe" />
    </div>
  </div>
  <div class="md:flex md:items-center mb-6">
    <div class="md:w-1/3">
      <label
        class="block text-gray-500 font-bold md:text-right mb-1 md:mb-0 pr-4"
        for="inline-username">
        Password
      </label>
    </div>
    <div class="md:w-2/3">
      <input
        class="bg-gray-200 appearance-none border-2 border-gray-200 rounded
        w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none
        focus:bg-white focus:border-purple-500"
        id="inline-username"
        type="password"
        placeholder="******************" />
    </div>
  </div>
  <div class="md:flex md:items-center mb-6">
    <div class="md:w-1/3" />
    <label class="md:w-2/3 block text-gray-500 font-bold">
      <input class="mr-2 leading-tight" type="checkbox" />
      <span class="text-sm">Send me your newsletter!</span>
    </label>
  </div>
  <div class="md:flex md:items-center">
    <div class="md:w-1/3" />
    <div class="md:w-2/3">
      <Button
        text="Sign Up"
        className="shadow bg-purple-500 hover:bg-purple-400 focus:shadow-outline
        focus:outline-none text-white" />
    </div>
  </div>
</form>

<p class="m-8" />

<form class="w-full max-w-lg">
  <div class="flex flex-wrap -mx-3 mb-6">
    <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
      <label
        class="block uppercase tracking-wide text-gray-700 text-xs font-bold
        mb-2"
        for="grid-first-name">
        First Name
      </label>
      <input
        class="appearance-none block w-full bg-gray-200 text-gray-700 border
        border-red-500 rounded py-3 px-4 mb-3 leading-tight focus:outline-none
        focus:bg-white"
        id="grid-first-name"
        type="text"
        placeholder="Jane" />
      <p class="text-red-500 text-xs italic">Please fill out this field.</p>
    </div>
    <div class="w-full md:w-1/2 px-3">
      <label
        class="block uppercase tracking-wide text-gray-700 text-xs font-bold
        mb-2"
        for="grid-last-name">
        Last Name
      </label>
      <input
        class="appearance-none block w-full bg-gray-200 text-gray-700 border
        border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none
        focus:bg-white focus:border-gray-500"
        id="grid-last-name"
        type="text"
        placeholder="Doe" />
    </div>
  </div>
  <div class="flex flex-wrap -mx-3 mb-6">
    <div class="w-full px-3">
      <label
        class="block uppercase tracking-wide text-gray-700 text-xs font-bold
        mb-2"
        for="grid-password">
        Password
      </label>
      <input
        class="appearance-none block w-full bg-gray-200 text-gray-700 border
        border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none
        focus:bg-white focus:border-gray-500"
        id="grid-password"
        type="password"
        placeholder="******************" />
      <p class="text-gray-600 text-xs italic">
        Make it as long and as crazy as you'd like
      </p>
    </div>
  </div>
  <div class="flex flex-wrap -mx-3 mb-2">
    <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
      <label
        class="block uppercase tracking-wide text-gray-700 text-xs font-bold
        mb-2"
        for="grid-city">
        City
      </label>
      <input
        class="appearance-none block w-full bg-gray-200 text-gray-700 border
        border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none
        focus:bg-white focus:border-gray-500"
        id="grid-city"
        type="text"
        placeholder="Albuquerque" />
    </div>
    <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
      <label
        class="block uppercase tracking-wide text-gray-700 text-xs font-bold
        mb-2"
        for="grid-state">
        State
      </label>
      <div class="relative">
        <select
          class="block appearance-none w-full bg-gray-200 border border-gray-200
          text-gray-700 py-3 px-4 pr-8 rounded leading-tight focus:outline-none
          focus:bg-white focus:border-gray-500"
          id="grid-state">
          <option>New Mexico</option>
          <option>Missouri</option>
          <option>Texas</option>
        </select>
        <div
          class="pointer-events-none absolute inset-y-0 right-0 flex
          items-center px-2 text-gray-700">
          <svg
            class="fill-current h-4 w-4"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20">
            <path
              d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757
              6.586 4.343 8z" />
          </svg>
        </div>
      </div>
    </div>
    <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
      <label
        class="block uppercase tracking-wide text-gray-700 text-xs font-bold
        mb-2"
        for="grid-zip">
        Zip
      </label>
      <input
        class="appearance-none block w-full bg-gray-200 text-gray-700 border
        border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none
        focus:bg-white focus:border-gray-500"
        id="grid-zip"
        type="text"
        placeholder="90210" />
    </div>
  </div>
</form>
