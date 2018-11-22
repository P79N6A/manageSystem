<template>
  <div className="login-page">
        <SimpleFooter />
        <UserLogin />
      </div>
</template>

<script>
import SimpleFooter from './components/SimpleFooter';
import UserLogin from './components/UserLogin';

export default {
  name: 'Login',
  components: {
    SimpleFooter,
    UserLogin,
  },
};
</script>
