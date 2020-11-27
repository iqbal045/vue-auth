<script>
import Home from '../pages/Home.vue'

const routes = [
  { path: '*', redirect: '/home' },
  { path: '/home', component: Home }
]

export default routes;
</script>
