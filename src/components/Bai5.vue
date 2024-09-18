<template>
  <div>
    <h2>Thông tin cá nhân</h2>
    <ul>
      <li>Họ và tên: {{ user.name }}</li>
      <li>Giới tính: {{ user.gender }}</li>
      <li>Ngày sinh: {{ user.date }}</li>
      <li>Email: {{ user.email }}</li>
      <li>Địa chỉ: {{ user.address }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        name: 'Nguyễn Văn A',
        gender: 'Nam',
        date: '06/03/2024',
        email: 'nva@gmail.com',
        address: 'Thanh Xuân, Hà Nội'
      }
    };
  }
};
</script>

<style>

</style>
