<template>
    <table class="table table-bordered"> 
        <thead> 
            <tr> 
                <th>#</th> 
                <th>First Name</th> 
                <th>Last Name</th> 
                <th>Username</th> 
            </tr> 
        </thead> 
        <tbody> 
            <tr> 
                <th scope="row">1</th> 
                <td>Mark</td> 
                <td>Otto</td>
                <td>@mdo</td>
            </tr> 
            <tr> 
                <th scope="row">2</th> 
                <td>Jacob</td> 
                <td>Thornton</td> 
                <td>@fat</td> 
            </tr>
        </tbody> 
    </table>
</template>

<script>
export default {
  name: 'TableComponent'
}
</script>

<style scoped>

</style>