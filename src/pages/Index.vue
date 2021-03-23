<template>
  <Layout>
    <div class="pt-8 md:pt-16">
      <div class="flex flex-col items-center">
        <div class="flex flex-col items-center mb-2 text-ui-primary">
          <Logo :width="200"/>
          <h2 class="text-3xl text-6xl font-black tracking-tighter border-none">
            TEAMSTATUS
          </h2>
        </div>
        <h1 class="text-4xl text-center lg:text-5xl">
          Look Available on Teams even when minding your own business.
        </h1>
        <p class="text-xl font-medium text-center">
          Don't want to work? Or you need to wash dishes? No problem! Just start the app and forget it.
          <br>
          <strong class="text-ui-primary">We got you covered!</strong>
        </p>
        
        <!--div class="py-4"> CODE SNIPPET
          <code class="block px-4 py-1 select-all bg-ui-border text-ui-typo">Start Teams available</code>
        </div-->
        
        
        <form class="flex justify-center mt-8"
            method="POST"
            data-netlify="true"
            data-netlify-honeypot="bot-field"
            netlify="true"
            name="waiting-list"
            action="success"
          >
          <input type="hidden" name="form-name" value="waiting-list" />
          <p hidden>
              <label> Don’t fill this out: <input name="bot-field" /> </label>
          </p>
          <input required type="email" name="email" placeholder="your_email@example.com" class="appearance-none block w-full text-gray-700 border
           border-indigo-600 rounded-lg py-4 px-6 leading-tight focus:outline-none focus:bg-white shadow-md">

          <button type="submit" tabindex="0"
            class="flex items-center px-6 py-4 ml-2 text-2xl font-bold leading-none text-white border rounded-lg shadow-md 
            bg-ui-primary border-ui-primary transition-all duration-200 ease-out transform hover:shadow-xl hover:translate-x-1 focus:outline-none focus:border-transparent"
          >
            Download
            <ArrowRightCircleIcon class="ml-4" size="1x" />
          </button>
        </form>

        <div class="flex justify-center mt-8">
          
          <g-link
            to="/docs/"
            class="flex items-center px-6 py-4 ml-auto text-l leading-none text-md font-medium text-center border rounded-lg bg-ui-sidebar hover:shadow-sm"
          >
            See how it works
            <ArrowRightCircleIcon class="ml-4" size="1x" />
          </g-link>
        </div>

        <p class="mt-8 text-center">
          Lightweight & <span class="border-b border-dashed border-ui-primary text-ui-primary">Discrete</span>.
        </p>

      </div>

      <div class="pt-8 mx-auto mt-8 border-t md:mt-16 md:pt-16 border-top border-ui-border max-w-screen-sm"></div>

      <h2 class="flex justify-center mt-8">
        Features
      </h2>

      <div class="flex flex-wrap justify-center -mx-4">
        
        <div class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3">
          <UserCheckIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Always Available
          </h3>
          <p class="text-lg text-left">
            Always look online on Microsoft Teams. Your boss will think you are working 9 to 5.<span class="border-b border-dashed border-ui-primary text-ui-primary">No seriously</span>.
          </p>
        </div>

        <div class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3">
          <PackageIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            No Installation Needed
          </h3>
          <p class="text-lg text-left">
            All headlines are indexed. Instant search powered by Fuse.js. Find what you are looking for in the <span class="border-b border-dashed border-ui-primary text-ui-primary">blink of an eye</span>.
          </p>
        </div>

        <div class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3">
          <ClockIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Set your working time
          </h3>
          <p class="text-lg text-left">
            Working late at night again? Enable dark mode with the click of a button.
          </p>
        </div>
      </div>

      <div class="pt-8 mx-auto mt-8 border-t md:mt-16 md:pt-16 border-top border-ui-border max-w-screen-sm"></div>
      
      <section class="py-8 px-4">
        <div class="flex flex-wrap -mx-8 text-center">
          <div class="w-full md:w-1/2 p-8 mb-4 md:mb-0">
            <h3 class="text-5xl font-semibold font-heading">$9 / mo</h3>
            <h4 class="font-bold tracking-wide uppercase text-ui-primary">Beginner</h4>
            <p class="flex-grow mt-4 mb-6 text-gray-500 leading-relaxed">Just enough paper for small business. Not enough to waste it on fluffy animals photos. The best quality and economy comes with Dunder Mifflin paper.</p>
            <a class="inline-block py-4 px-8 leading-none text-indigo-600 bg-indigo-50 hover:bg-indigo-100 font-semibold rounded shadow" href="#">Contact sales</a>
          </div>
          <div class="w-full md:w-1/2 p-8 mb-4 md:mb-0 md:border-l">
            <h3 class="text-5xl font-semibold font-heading">$19 / mo</h3>
            <h4 class="font-bold tracking-wide uppercase text-ui-primary">Pro</h4>
            <p class="mt-4 mb-6 text-gray-500 leading-relaxed">A lot of customization options including: set your working hours. Or set the time duration.</p>
            <a class="inline-block py-4 px-8 leading-none text-white bg-indigo-600 hover:bg-indigo-700 font-semibold rounded shadow" href="#">Contact sales</a>
          </div>
        </div>
      </section>
      
      </div>

      <div class="pt-8 mx-auto mt-8 border-t md:mt-16 md:pt-16 border-top border-ui-border max-w-screen-sm"></div>

      <section class="py-12 px-4">
        <div class="max-w-3xl mx-auto">
          <h2 class="text-4xl text-center mb-6 font-semibold font-heading">Frequently Asked Questions</h2>
          <div class="p-4 mb-2 border-b">
            <button class="flex w-full text-left mb-4"><span class="flex-grow font-semibold">How does Dunder Mifflin paper differ from other products?</span><svg class="text-indigo-700 w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg></button>
            <p class="mt-1">Paper produced with love, devotion, passion - is not the same paper. Our supplies are extra strong, and you’re going to need the paper-tear up-master to destroy just one sheet. It’s also suited for every available printer.</p>
          </div>
          <div class="p-4 mb-2 border-b">
            <button class="flex w-full text-left mb-4"><span class="flex-grow font-semibold">Why choose Dunder Mifflin instead of some huge paper producer?</span><svg class="text-indigo-700 w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg></button>
            <p class="hidden mt-1">You know that feeling when you are waiting on the phone for hours to contact your supplier? Sometimes they even have a waiting time music prepared for that. In Dunder Mifflin, you can get help immediately, and each of our customers receives an individual assistant. For us, companies are people - not numbers, so we take care of each of them.</p>
          </div>
          <div class="p-4 mb-2 border-b">
            <button class="flex w-full text-left mb-4"><span class="flex-grow font-semibold">When I will receive the products?</span><svg class="text-indigo-700 w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg></button>
            <p class="hidden mt-1">If you buy one of our business plans, you will receive the supplies every first Monday of the month. However, you can also purchase paper separately. Our employees will make sure that you will receive the products in the next business days.</p>
          </div>
          <div class="p-4 mb-2 border-b">
            <button class="flex w-full text-left mb-4"><span class="flex-grow font-semibold">How long does it take to finalize the deal?</span><svg class="text-indigo-700 w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg></button>
            <p class="hidden mt-1">The whole process depends on your decision. If you sign the contract immediately, we can start official cooperation in the next two business days.</p>
          </div>
        </div>
      </section>

      <section class="py-12 px-4">
        <h2 class="text-4xl mb-10 text-center font-semibold font-heading">Contact</h2>
        <div class="w-full max-w-2xl mx-auto mb-8">
          <form>
            <div class="flex mb-4 -mx-2">
              <div class="w-1/2 px-2">
                <input class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-50 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none" type="email" placeholder="Name">
              </div>
              <div class="w-1/2 px-2">
                <input class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-50 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none" type="email" placeholder="Email">
              </div>
            </div>
            <div class="mb-4">
              <textarea class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-50 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none" placeholder="Write something..." rows="5"></textarea>
            </div>
            <div>
              <button class="inline-block w-full py-4 px-8 leading-none text-white bg-indigo-700 hover:bg-indigo-700 font-semibold rounded shadow">Submit</button>
            </div>
          </form>
        </div>
        <div class="text-center">
          <p class="mb-2">Or just email us on</p><a class="text-indigo-700 hover:underline" href="#">info@teamstatus.com</a>
        </div>
      </section>

    </div>
  </Layout>
</template>

<script>
import Logo from '@/components/Logo';
import { ArrowRightCircleIcon, ZapIcon, CodeIcon, MoonIcon, SearchIcon, UserCheckIcon, ClockIcon, PackageIcon, MailIcon} from 'vue-feather-icons';

export default {
  components: {
    Logo,
    ArrowRightCircleIcon,
    ZapIcon,
    CodeIcon,
    MoonIcon,
    SearchIcon,
    UserCheckIcon,
    ClockIcon,
    PackageIcon,
    MailIcon
  },

  metaInfo() {
    const title = 'Prevent the Away Status on Microsoft Teams';
    const description = 'Always look Available on Microsoft Teams even when you are not working. Forget the Away Status on Microsoft Teams';

    return {
      title: title,
      meta: [
        {
          name: 'description',
          content: description
        },
        {
          key: 'og:title',
          name: 'og:title',
          content: title,
        },
        {
          key: 'twitter:title',
          name: 'twitter:title',
          content: title,
        },
        {
          key: 'og:description',
          name: 'og:description',
          content: description,
        },
        {
          key: 'twitter:description',
          name: 'twitter:description',
          content: description,
        },
      ]
    }
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
