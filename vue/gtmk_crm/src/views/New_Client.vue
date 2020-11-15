<template>
  <div class="new_client">
    <div class="columns">

        <div class="column is-3 is-offset-0">
            <h3 class="subtitle">Navigation part</h3>
        </div>

        <div class="column is-5 is-offset-1">

            <h1 class="title">Add new client</h1>

            <form>

                <div class="field">
                    <label class="label">Client name</label>
                        <div class="control">
                            <input class="input" type="text">
                        </div>
                </div>

                <div class="field">
                    <div class="control">
                        <button class="button is-link">Submit</button>
                    </div>
                </div>

            </form>

        </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'NewClient',

}
</script>