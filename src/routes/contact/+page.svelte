<script lang="ts">
  import NavBar from "../../components/NavBar.svelte";
  import { redirect } from "@sveltejs/kit";

  // let name: string;
  // let email: string;
  // let content: string;
  // let taken: boolean = false;

  // async function submitForm() {
  //   const data = { name: name, email: email, content: content };
  //   const res = await fetch("https://api.jbstepan.com/contact/create", {
  //     method: "POST",
  //     headers: { "Content-Type": "application/json", "Access-Control-Allow-Origin": "*" },
  //     body: JSON.stringify(data),
  //   });

  //   if (res.status === 200) {
  //     alert("200");
  //   } else if (res.status === 400) {
  //     alert("400");
  //   } else if (res.status === 401) {
  //     alert("401");
  //   } else if (res.status === 500) {
  //     alert("500");
  //   }
  // }
</script>

<svelte:head>
  <title>Contact</title>
</svelte:head>

<!-- <main>
  <NavBar />
  <h1>Contact Form</h1>
  <center>
    <form on:submit={submitForm}>
      <input type="text" placeholder="EMail" bind:value={email} /><br /><br />
      <input type="text" placeholder="Name" bind:value={name} /><br /><br />
      <textarea
        cols="30"
        rows="10"
        placeholder="What would you like to contact about?"
        bind:value={content}
      /><br /><br />
      <button type="submit">Submit</button>
    </form>
  </center>
</main> -->

<main>
  <h1>Currently down! 🤒</h1>
</main>

<style>
  :root {
    font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
    line-height: 1.5;
    font-weight: 400;

    color-scheme: light dark;
    color: rgba(255, 255, 255, 0.87);
    background-color: #242424;

    font-synthesis: none;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-text-size-adjust: 100%;
  }
  /*  main {
    text-align: center;
    margin-top: 6.5rem;
  }

  .submit {
    transition: 300ms;
    transform: scale(1);
    background-color: rgb(188, 188, 188);
    color: black;
    padding: 0.7rem;
    outline: transparent;
    border: transparent;
    font-size: 25px;
    cursor: pointer;
    text-decoration: none;
    border-radius: 5px;
  }

  .submit:hover {
    transition: 300ms;
    transform: scale(1.2);
    background-color: white;
    outline-color: white;
    outline: black;
    text-decoration: none;
  }

  input[type="text"],
  textarea {
    font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
    padding: 6px 12px;
    margin-bottom: 0.5rem;
    background-color: rgb(188, 188, 188);
    color: black;
    border: 1px solid transparent;
    border-radius: 4px;
    box-shadow: none;
    box-sizing: content-box;
    font-size: 18px;
  }

  input[type="text"]:focus,
  textarea:focus {
    background-color: white;
  }

  form {
    border: white 6px solid;
    border-radius: 5px;
    padding: 6px 16px;
    max-width: max-content;
  }
  */
</style> 
