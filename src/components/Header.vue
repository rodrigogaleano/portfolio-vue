<template>
   <header class="header">
        <nav>
          <h1>Mobile developer</h1>
        </nav>
        <nav class="center-nav">
          <ul>
            <li>
              <a href="#">Index</a>
            </li>
            <li>
              <a href="#">About</a>
            </li>
          </ul>
        </nav>
        <nav class="message-link">
          <a href="#">Send me a message</a>
        </nav>
      </header>
</template>


<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
}

.center-nav ul {
    display: flex;
    gap: 2rem;
    list-style: none;
    padding: 0;
    margin: 0;
}

.center-nav a {
    text-decoration: none;
    color: #999;
}

.center-nav a.active {
    color: #000;
}

.message-link {
    text-decoration: underline;
    color: #000;
}
</style>
