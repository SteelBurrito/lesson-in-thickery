<template>
    <div class="container">
        <div class="row justify-content-md-center">
            <h1>THICC TRANSLATOR</h1>
        </div>
        <div class="row justify-content-md-center">
            <div class="form">
                <div class="col">
                    <div class="form-group">
                        <label for="textInput">Enter Text</label>
                        <textarea v-model="textInput" class="form-control" id="textInput" rows="3"></textarea>
                    </div>
                </div>
                <div class="col">
                    <div class="form-group">
                        <label for="textOutput">Translated Text</label>
                        <textarea v-model="textOutput" class="form-control-plaintext" id="textOutput" rows="3" readonly></textarea>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      textInput: '',
      textOutput: '',
    };
  },
  methods: {
    textTranslate() {},
  },
};
</script>