<template>
  <div class="mt-8">
    <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Frontend
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
         <li class="flex items-center" title="HTML5">
          <Html class="h-10 w-10 rounded-sm drop-shadow-sm"></Html>
        </li>
         <li class="flex items-center" title="React">
          <React class="h-10 w-10"></React>
        </li>
        <li class="flex items-center" title="Angular">
          <Angular class="h-10 w-10"></Angular>
        </li>
        <li class="flex items-center" title="SCSS">
          <Scss class="h-10 w-10"></Scss>
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Backend
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center" title=".NET">
          <DotNet class="h-10 w-100"></DotNet>
        </li>
        <li class="flex items-center" title="AspNet">
          <Aspnet class="h-10 w-100"></Aspnet>
        </li>
        <li class="flex items-center" title="Azure Function">
          <AzureFunctions class="h-10 w-10"></AzureFunctions>
        </li>

      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Languages
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center" title="C#">
          <Csharp class="h-10 w-10"></Csharp>
        </li>
        <li class="flex items-center" title="JavaScript">
          <Javascript class="h-10 w-10"></Javascript>
        </li>
        <li class="flex items-center" title="TypeScript">
          <Typescript class="h-10 w-10"></Typescript>
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Tools and Methodologies
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center" title="Git">
          <Git class="h-10 w-10"></Git>
        </li>
        <li class="flex items-center" title="Azure">
          <Azure class="h-10 w-10"></Azure>
        </li>
        <li class="flex items-center" title="Azure DevOps">
          <AzureDevOps class="h-10 w-10"></AzureDevOps>
        </li>
        <li class="flex items-center" title="SCRUM">
          <SCRUM class="h-10 w-10"></SCRUM>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import Javascript from "../assets/devicon/javascript.svg?inline";
import Html from "../assets/devicon/html.svg?inline";``
import Css from "../assets/devicon/css.svg?inline";
import Vuejs from "../assets/devicon/vuejs.svg?inline";
import TailwindCss from "../assets/devicon/tailwindcss.svg?inline";
import Nuxt from "../assets/devicon/nuxt.svg?inline";
import Bootstrap from "../assets/devicon/bootstrap.svg?inline";
import Laravel from "../assets/devicon/laravel.svg?inline";
import Node from "../assets/devicon/node.svg?inline";
import Csharp from "../assets/devicon/csharp.svg?inline";
import React from "../assets/devicon/react.svg?inline";
import Typescript from "../assets/devicon/typescript.svg?inline";
import Scss from "../assets/devicon/scss.svg?inline";
import Angular from "../assets/devicon/angular.svg?inline";
import AzureFunctions from "../assets/devicon/azure-functions.svg?inline";
import Aspnet from "../assets/devicon/aspnet.svg?inline";
import Git from "../assets/devicon/git.svg?inline";
import Azure from "../assets/devicon/azure.svg?inline";
import AzureDevOps from "../assets/devicon/azure-devops.svg?inline";
import SCRUM from "../assets/devicon/scrum.svg?inline";
import DotNet from "../assets/devicon/dotnet.svg?inline";

export default {
  components: {
    Javascript,
    Html,
    Css,
    Bootstrap,
    Vuejs,
    TailwindCss,
    Nuxt,
    Laravel,
    Node,
    Csharp,
    React,
    Typescript,
    Scss,
    Angular,
    AzureFunctions,
    Aspnet,
    Git,
    Azure,
    AzureDevOps,
    SCRUM,
    DotNet
  },
};
</script>
