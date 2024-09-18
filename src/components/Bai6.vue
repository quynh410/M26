<template>
  <div>
    <b>Họ và tên: {{ formatName(user) }}</b>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        firstName: 'Nguyễn Văn',
        lastName: 'Nam'
      }
    };
  },
  methods: {
    formatName(user) {
      return `${user.firstName} ${user.lastName}`;
    }
  }
};
</script>

<style>
b {
  font-size: 20px;
}
</style>
