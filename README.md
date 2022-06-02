
<!---
JonyNav/JonyNav is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!-- Modal -->
<div id="modal-agrega-flujoAt" class="modal fade" role="dialog">
    <div class="modal-dialog" style="width: 60%;">

<!-- Modal -->
<div id="modal-agrega-flujoAt" class="modal fade" role="dialog">
    <div class="modal-dialog" style="width: 60%;">

        <!-- Modal content-->
        <div class="modal-content">
            <div class="modal-header">
                <h4 class="modal-title">Flujos de Autorización</h4>
            </div>
			
            <div class="modal-body" >
                <form  id="frmUsuario" name="frmUsuario" method="post" style="padding: 0 15px;">
                    <input type="hidden" id="id_usuario" name="id_usuario" value="">

                    <div class="row" style="margin-bottom: 50px;">
                        
						  <label>Nombre del Flujo</label>
                            <input type="input" class="form-control input-sm" id="nombre" name="nombre" 
                                   placeholder="Nombre del Flujo">
                            <div name="nombrediv" id="nombrediv" class="errordiv"></div>
                            
                    </div>
					
					 <div class="row" style="margin-bottom: 5px;text-align: left;margin: 10px 0 10px 0; border-bottom: 1.5pt #4b4e53 solid;"  >
                        <div class="col-lg-5" >
                           <label > Datos Generales</label>
                        </div>
                       
                    </div>
					
					 <div class="col-lg-12 form-group" style="margin-bottom: 5px;">
                        <div class="col-lg-5" style="padding-right: 5px;padding-left: 0px;">
                           <label > Nombre del Dato</label>
                        </div>
							<input type="input" style="width: 25px; width: 400px" name="nombre" padding="center" placeholder="Nombre del Flujo">
						<div name="nombrediv" id="nombrediv" class="errordiv"></div>
                        <div  class="col-lg-5" style="text-align: end">                            
                        </div>
                    </div>				    
					
					<div class="col-lg-12 form-group"style="margin-bottom: 10px;">
                        <div class="col-lg-5" style="padding-right: 5px;padding-left: 0px;">
                           <label > Tipo de Dato</label>
                        </div>
							<select  id="rol" name="rol" style="width: 60px; width: 400px">
                                <option value="">Ingresar Tipo de Dato</option>
                                <option value="">Texto</option>
								<option value="">Fecha</option>
								<option value="">Cantidad</option>
								<option value="">Correo</option>
								<option value="">Número</option>
                            </select>                    
                            <div name="roldiv" id="roldiv" class="errordiv"></div>                        
                    </div>
					
						<div class="col-lg-12 form-group" style="margin-bottom: 10px;">
							<div class="col-lg-5" style="padding-right: 5px;padding-left: 0px;">
                           <label > Longitud</label>
								</div>
								<input type="input" style="width: 25px; width: 400px"  id="nombre" name="nombre" placeholder="Nombre del Flujo">
                            <div name="nombrediv" id="nombrediv" class="errordiv"></div>					  
						</div>
						
						 <div  class="form-group" style="text-align: right;margin-bottom: 10px;">
                                <button class="btn btn-primary add-grupo" > Agregar + </button>						     
								<button class="btn btn-link remove-grupo" > - Quitar </button>	
							
                        </div>
						
						
						
						<div class="container-data-report col-lg-12 col-md-12 col-sm-12 col-xs-12" style="margin-bottom:60px;">
							<table id="example" class="row-border order-column hover" style="width:100%">
							<thead class="box box-primary">
                            <tr>
                                <th>Nombre del Dato</th>
                                <th>Tipo de Dato</th>
                                <th>Longitud</th>
                                <th>Acciones</th>                              
                            </tr>
							</thead>                       
							</table>
						</div>						
						
						 <div class="row" style="margin-bottom: 5px;text-align: left;margin: 10px 0 10px 0; border-bottom: 1.5pt #4b4e53 solid;"  >
							<div class="col-lg-5" >
								<label > Autorizaciones</label>
							</div>                       
						 </div>
						
						
						<div class="col-lg-12 form-group" style="margin-bottom: 5px;">
                        <div class="col-lg-5" style="padding-right: 5px;padding-left: 0px;">
                           <label > Rol/Correo del Autorizador </label>
                        </div>
							<input type="input" style="width: 25px; width: 400px" name="nombre" padding="center" placeholder="Capturar Rol/Correo del Autorizador">
						<div name="nombrediv" id="nombrediv" class="errordiv"></div>
                        <div  class="col-lg-5" style="text-align: end">                            
                        </div>
						</div>			
						
						<div class="col-lg-12 form-group" style="margin-bottom: 5px;">
                        <div class="col-lg-5" style="padding-right: 5px;padding-left: 0px;">
                           <label > Direccion - Departamento </label>
                        </div>
							<input type="input" style="width: 25px; width: 400px" name="nombre" padding="center" placeholder="Será con mysql">
						<div name="nombrediv" id="nombrediv" class="errordiv"></div>
                        <div  class="col-lg-5" style="text-align: end">                            
                        </div>
						</div>	
						
						 <div  class="form-group" style="text-align: right;margin-bottom: 10px;">
                                <button class="btn btn-primary" >Agregar +</button>						     
								<button class="btn btn-link" > - Quitar </button>	
							
                        </div>
						
						<div class="container-data-report col-lg-12 col-md-12 col-sm-12 col-xs-12" style="margin-bottom:60px;">
							<table id="example" class="row-border order-column hover" style="width:100%">
							<thead class="box box-primary">
                            <tr>
                                <th>Rol</th>
                                <th>Dirección</th>
                                <th>Orden</th>
                                <th>Acciones</th>                              
                            </tr>
							</thead>                       
							</table>
						</div>				
						

						
						<div class="form-group" style="text-align: right">                       
							<button type="button" class="btn btn-primary" onclick="javascript:guardarDatos()">Guardar</button>                        
							<button type="button" class="btn btn-link cancelar" data-dismiss="modal">Cancelar </button>
						</div>
					
					
                    </div>
					

                </form>
            </div>
        </div>

    </div>
</div>

<script type="text/javascript">
   

</script>
