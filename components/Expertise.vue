<template>
  <div class="mt-8">
    <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Programming languages
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
        <!-- <li class="flex items-center">
          <Html class="h-10 w-10 rounded-sm drop-shadow-sm"></Html>
        </li>

        <li class="flex items-center">
          <Css class="h-10 w-10 rounded-sm drop-shadow-sm"></Css>
        </li> -->
        <li class="flex items-center">
          <Python class="h-10 w-10"></Python>
        </li>
        <li class="flex items-center">
          <Java class="h-10 w-10"></Java>
        </li>
        <li class="flex items-center">
          <R class="h-10 w-10"></R>
        </li>
        <li class="flex items-center">
          <Matlab class="h-10 w-10"></Matlab>
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Software libraries
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center">
          <Numpy class="h-10 w-10"></Numpy>
        </li>
        <li class="flex items-center">
          <Pandas class="h-10 w-10"></Pandas>
        </li>
        <li class="flex items-center">
          <Pytorch class="h-10 w-10"></Pytorch>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import Python from "../assets/devicon/python.svg?inline";
import Java from "../assets/devicon/java.svg?inline";
import R from "../assets/devicon/r.svg?inline";
import Matlab from "../assets/devicon/matlab.svg?inline";
import Numpy from "../assets/devicon/numpy.svg?inline";
import Pandas from "../assets/devicon/pandas.svg?inline";
import Pytorch from "../assets/devicon/pytorch.svg?inline";
export default {
  components: {
    Python,
    Java,
    R,
    Matlab,
    Numpy,
    Pandas,
    Pytorch,
  },
};
</script>
