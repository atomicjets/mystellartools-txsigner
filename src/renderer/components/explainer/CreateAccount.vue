<template>
    <div>
        <table>
            <tr>
                <td><b>Account</b></td>
                <td><span v-text="operation.destination"></span></td>
            </tr>
            <tr>
                <td><b>Starting balance</b></td>
                <td><span v-text="operation.startingBalance"></span> XLM</td>
            </tr>
        </table>
    </div>
</template>

<script>
  export default {
    props: ['operation']
  }
</script>