<script>
  export default {
    name: 'ContactUs',
  }
</script>

<template>
    <div>
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>
        
        <button type="submit">Send</button>
      </form>
    </div>
</template>
  
  
  