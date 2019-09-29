<script>
  import Card from "./Molecules/MoleculeCard.svelte";
  import Progress from "./Molecules/MoleculeProgress.svelte";
  import Pricing from "./Molecules/MoleculePricing.svelte";
  import NavBar from "./Molecules/NavBarNew.svelte";
  import RoundedButton from "./Molecules/Atoms/Buttons/RoundedButton.svelte";
  import SocialMediaButton from "./Molecules/Atoms/Buttons/SocialMediaButton.svelte";
</script>

<div class="bg-gray-200">
  <NavBar />
  <p class="m-8" />
  <div class="bg-gray-800">
    <div class="bg-gray-700 w-full lg:w-1/2 mx-auto flex flex-col">
      <img
        alt=""
        src="https://rscard.px-lab.com/startuper/wp-content/uploads/sites/2/2015/11/startuper-1-299x347.jpg"
        class="lg:w-1/3 sm:w-full" />
      <div>
        <div
          class="bg-orange-600 w-full lg:w-1/2 mx-auto flex flex-row
          justify-center" />
      </div>
      <div class="speech-bubble">HELLO TEST</div>
    </div>
    <div
      class="bg-orange-600 w-full lg:w-1/2 mx-auto flex flex-row justify-center">

      <SocialMediaButton />
      <SocialMediaButton />
      <SocialMediaButton />
      <SocialMediaButton />
      <SocialMediaButton />
    </div>

    <p class="m-8" />
    <Progress label="WordPress" value="90" />
    <Progress label="CSS" value="40" />
    <p class="m-8" />
    <Pricing title="" val1="" val2="" val3="" val4="" val5="" val6="" />

    <p class="m-8" />

    <div class="container mx-auto">
      <span>Fill</span>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-2 px-4
        rounded">
        Light
      </button>
      <button
        class="bg-purple-200 text-purple-900 hover:bg-purple-300 py-2 px-4
        rounded">
        Dark
      </button>
      <button
        class="bg-purple-500 text-purple-100 py-2 px-4 rounded opacity-50
        cursor-not-allowed">
        Light Disabled
      </button>
      <button
        class="bg-purple-200 text-purple-900 py-2 px-4 rounded opacity-50
        cursor-not-allowed">
        Dark Disabled
      </button>
    </div>

    <p class="m-8" />

    <div class="container mx-auto">
      <span>Outline</span>
      <button
        class="border-purple-700 border text-purple-700 hover:bg-purple-200 py-2
        px-4 rounded">
        Light
      </button>
      <button
        class="border-purple-300 border text-purple-300 hover:bg-purple-800 py-2
        px-4 rounded">
        Dark
      </button>
      <button
        class="border-purple-700 border text-purple-700 py-2 px-4 rounded
        opacity-50 cursor-not-allowed">
        Light Disabled
      </button>
      <button
        class="border-purple-300 border text-purple-300 py-2 px-4 rounded
        opacity-50 cursor-not-allowed">
        Dark Disabled
      </button>
    </div>

    <p class="m-8" />

    <div class="container mx-auto">
      <span>Flat</span>
      <button class="text-purple-700 hover:bg-purple-200 py-2 px-4 rounded">
        Light
      </button>
      <button class="text-purple-300 hover:bg-purple-800 py-2 px-4 rounded">
        Dark
      </button>
      <button
        class="text-purple-700 py-2 px-4 rounded opacity-50 cursor-not-allowed">
        Light Disabled
      </button>
      <button
        class="border text-purple-300 py-2 px-4 rounded opacity-50
        cursor-not-allowed">
        Dark Disabled
      </button>

    </div>

    <p class="m-8" />

    <div class="container mx-auto">
      <span>Size</span>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-1 px-2
        text-xs rounded">
        X-Small
      </button>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-2 px-3
        text-sm rounded">
        Small
      </button>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-3 px-4
        text-base rounded">
        Default
      </button>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-4 px-6
        text-xl rounded">
        Large
      </button>
    </div>

    <p class="m-8" />

    <div class="container mx-auto">
      <span>Shape</span>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-2 px-4
        rounded-none">
        Flat
      </button>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-2 px-4
        rounded">
        Rounded
      </button>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-2 px-4
        rounded-lg">
        Rounded-LG
      </button>
      <button
        class="bg-purple-500 text-purple-100 hover:bg-purple-600 py-2 px-4
        rounded-full">
        Pill button
      </button>
    </div>

    <p class="m-8" />

    <div class="container mx-auto">
      <span>Icon</span>
      <button
        class="bg-purple-300 hover:bg-purple-400 text-purple-800 font-bold py-2
        px-4 rounded inline-flex items-center">
        <svg
          class="fill-current w-4 h-4 mr-2"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20">
          <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
        </svg>
        <span>Icon on Left</span>
      </button>
      <button
        class="bg-green-300 hover:bg-green-400 text-green-800 font-bold py-2
        px-4 rounded inline-flex items-center">
        <span>Icon on Right</span>
        <svg
          class="fill-current w-4 h-4 ml-2"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20">
          <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
        </svg>
      </button>
      <button
        class="bg-red-300 hover:bg-red-400 text-red-800 font-bold py-3 px-4
        rounded inline-flex items-center">
        <svg
          class="fill-current w-4 h-4"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20">
          <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
        </svg>
      </button>
      <button
        class="bg-blue-300 hover:bg-blue-400 text-blue-800 font-bold py-3 px-3
        rounded-full inline-flex items-center">
        <svg
          class="fill-current w-4 h-4"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20">
          <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
        </svg>
      </button>
    </div>

    <p class="m-8" />

    <p class="m-8" />

    <p class="m-8" />

    <Card title="New title" subtitle="Sub" />
    <p class="m-8" />
    <button class="hvr-sweep-to-right">Test button</button>
    <RoundedButton
      text="Button"
      className="bg-blue-500 hover:bg-blue-400 text-white border-b-4
      border-blue-700 hover:border-blue-500" />
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
        <label
          class="block text-gray-700 text-sm font-bold mb-2"
          for="username">
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
        <label
          class="block text-gray-700 text-sm font-bold mb-2"
          for="password">
          Password
        </label>
        <input
          class="shadow appearance-none border border-red-500 rounded w-full
          py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none
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
        <RoundedButton
          text="Sign Up"
          className="shadow bg-purple-500 hover:bg-purple-400
          focus:shadow-outline focus:outline-none text-white" />
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
          border-gray-200 rounded py-3 px-4 mb-3 leading-tight
          focus:outline-none focus:bg-white focus:border-gray-500"
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
            class="block appearance-none w-full bg-gray-200 border
            border-gray-200 text-gray-700 py-3 px-4 pr-8 rounded leading-tight
            focus:outline-none focus:bg-white focus:border-gray-500"
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
</div>
