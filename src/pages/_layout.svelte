<style lang="scss">
main {
   text-align: center;
   padding: 1em;
   max-width: 240px;
   margin: 0 auto;
   &:hover {
      background: blue;
   }
}

@media (min-width: 640px) {
   main {
      max-width: none;
   }
}
</style>
<main><slot/></main>