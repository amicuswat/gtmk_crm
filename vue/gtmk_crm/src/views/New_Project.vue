<template>
  <div class="new_project">
    <div class="columns">

        <div class="column is-3 is-offset-0">
            <h3 class="subtitle">Navigation part</h3>
        </div>

        <div class="column is-5 is-offset-1">

            <h1 class="title">Add new project</h1>

            <form>



                <div class="field">
                    <label class="label">Client</label>
                        <div class="select">
                            <select>
                              <option value="client1">Client 1</option>
                              <option value="client2">Best client</option>
                            </select>
                        </div>
                </div>

                <div class="field">
                    <label class="label">Project code</label>
                        <div class="control">
                            <input class="input" type="text">
                        </div>
                </div>

                <div class="field">
                    <label class="label">Deadline</label>
                        <div class="control">
                            <input class="input" type="text">
                        </div>
                </div>

                <div class="field">
                    <label class="label">Link to Smartcat</label>
                        <div class="control">
                            <input class="input" type="text">
                        </div>
                </div>

                <div class="field">
                    <label class="label">Link to Bitrix</label>
                        <div class="control">
                            <input class="input" type="text">
                        </div>
                </div>

                <div class="field">
                    <label class="label">Client's comment</label>
                        <div class="control">
                            <input class="input" type="text">
                        </div>
                </div>

                <div class="field">
                    <label class="label">Source language</label>
                        <div class="control">
                            <input class="input" type="text">
                        </div>
                </div>

                <div class="field">
                    <label class="label">Target language</label>
                        <div class="control">
                            <textarea class="textarea" placeholder="Something special from client?"></textarea>

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
  name: 'NewProject',

}
</script>