<template>
    <Page>
        <ActionBar title="Fath native App!"/>
        <GridLayout columns="*" rows="*">
            <Label class="message" :text="msg" col="0" row="0"/>
            <button class="bt">hello there bt</button>
            <label for="x">fath</label>
            <input type="text" name="x" id="x">
        </GridLayout>
    </Page>
</template>

<script >
  export default {
    data() {
      return {
        msg: 'Hello World!'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
    .bt{
      font-size: 10px;
      width: 200px;
      background: #333333;
      color: white;
    }
</style>
