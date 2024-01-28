## We must follow css and js link pattern include your index page 
## css pattern
  <link rel="stylesheet" href="./css/bootstrap.min.css">
  <link rel="stylesheet" href="./css/dataTables.bootstrap5.min.css">
  <link rel="stylesheet" href="./css/buttons.bootstrap5.min.css">
  
## js pattern 
 <script src="./js/jquery-3.7.0.js"></script>
  <script src="./js/jquery.dataTables.min.js"></script>
  <script src="./js/dataTables.bootstrap5.min.js"></script>
  <script src="./js/dataTables.buttons.min.js"></script>
  <script src="./js/buttons.bootstrap5.min.js"></script>
  <script src="./js/jszip.min.js"></script>
  <script src="./js/pdfmake.min.js"></script>
  <script src="./js/vfs_fonts.js"></script>
  <script src="./js/buttons.html5.min.js"></script>
  <script src="./js/buttons.print.min.js"></script>

  ## jquery 
    <script>
    $(document).ready(function() {
      var table = $('#example').DataTable( {
          lengthChange: true,
          buttons: [ 'copy', 'excel', 'pdf', 'colvis' ]
      } );
   
      table.buttons().container()
          .appendTo( '#example_wrapper .col-md-6:eq(0)' );
  } );
  </script>
  
