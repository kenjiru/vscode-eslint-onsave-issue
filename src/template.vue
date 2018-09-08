<template>
  <font-awesome-icon v-if="statusOptions.icon" :icon="statusOptions.icon" :spin="statusOptions.isIconSpin" :class="['saving-indicator', 'pl0', 'pt-1', statusOptions.iconClasses]"/>
</template>
