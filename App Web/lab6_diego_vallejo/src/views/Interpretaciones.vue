<template>

	<div id="app">
		<v-app>
			<v-main>
				<v-container>
					<v-row>
						<v-col sm="12" lg="12" >
							<div class="d-flex justify-center ">
								<h1 >
									Schrodinger's cat
								</h1>
								<div > 
									<v-img 
										src="../assets/cat.png"
										max-height="50"
										max-width="50"
									>
									</v-img>
								</div>
							</div>
						</v-col>
					</v-row>
					<v-row>
						<v-col>
							<v-card
							elevation="4"
							outlined
							class="d-flex justify-space-around grey lighten-2"
							style="padding: 10px;"
							>
								<router-link style="text-decoration: none;" to="/">Home</router-link>
								<router-link style="text-decoration: none;" to="/introduccion">Introduccion</router-link>
								<router-link style="text-decoration: none;" to="/interpretaciones">Interpretaciones</router-link>
								<router-link style="text-decoration: none;" to="/contacto">Contacto</router-link>
							</v-card>
						</v-col>
					</v-row>
					<v-row>
						<v-col sm="12" lg="4" >
							<v-card
								elevation="4"
								outlined
								class="grey lighten-2"
								style="padding: 20px"
							>
								<v-card-title class="d-flex justify-center">
									Temas de Interes
								</v-card-title>
								<h3 class="d-flex flex-column" >
									<a style="text-decoration: none;" href="https://es.wikipedia.org/wiki/Erwin_Schr%C3%B6dinger">
										Erwin Schrodinger
									</a>
									<br/>
									<a style="text-decoration: none;" href="https://es.wikipedia.org/wiki/Mec%C3%A1nica_cu%C3%A1ntica">
										Mecanica Cuantica
									</a>
									<br/>
									<a style="text-decoration: none;" href="https://es.wikipedia.org/wiki/Felis_silvestris_catus#:~:text=El%20gato%20dom%C3%A9stico%E2%80%8B%E2%80%8B,convivencia%20con%20el%20ser%20humano.">
										Gatos
									</a>
									<br/>
								</h3>
							</v-card>
						</v-col>
						<v-col sm="12" lg="8" >
							<v-card
								elevation="4"
								outlined
								class="grey lighten-2"
								style="padding: 20px"
							>
                                <div style="padding: 15px;" class="text-justify">
                                    <section>
                                        <p>
                                            Schr??dinger pretend??a que su experimento mental fuera una discusi??n de la paradoja EPR, llamada as?? por sus autores Einstein, Podolsky y Rosen en 1935. La paradoja EPR destac?? la naturaleza contraintuitiva de las superposiciones cu??nticas, en las que un sistema cu??ntico como un ??tomo o el fot??n puede existir como una combinaci??n de m??ltiples estados correspondientes a diferentes resultados posibles.
                                        </p>
                                        <p>
                                            La teor??a predominante, llamada interpretaci??n de Copenhague dice que un sistema cu??ntico permanece en superposici??n hasta que interact??a con el mundo externo o es observado por ??l. Cuando esto sucede, la superposici??n colapsa en uno u otro de los posibles estados definidos. El experimento EPR muestra que un sistema con m??ltiples part??culas separadas por grandes distancias puede estar en tal superposici??n. Schr??dinger y Einstein intercambiaron cartas sobre el art??culo EPR de Einstein, en el curso del cual Einstein se??al?? que el estado de un barril inestable de p??lvora, despu??s de un tiempo, contendr?? una superposici??n de estados explotados y sin explotar.
                                        </p>
                                        <p>
                                            Para ilustrar mejor, Schr??dinger describi?? c??mo se podr??a, en principio, crear una superposici??n en un sistema a gran escala haci??ndolo dependiente de una part??cula cu??ntica que estaba en una superposici??n. Propuso un escenario con un gato en una c??mara de acero cerrada, en el que la vida o la muerte del gato depend??a del estado de un ??tomo radiactivo, si se hab??a descompuesto y emitido radiaci??n o no. Seg??n Schr??dinger, la interpretaci??n de Copenhague implica que el gato permanece vivo y muerto hasta que se observa el estado. Schr??dinger no deseaba promover la idea de gatos muertos y vivos como una posibilidad seria; por el contrario, pretend??a que el ejemplo ilustrara el absurdo de la visi??n existente de la mec??nica cu??ntica.
                                        </p>
                                        <p>
                                            Sin embargo, desde la ??poca de Schr??dinger, los f??sicos han propuesto otras interpretaciones de la mec??nica cu??ntica, algunos de los cuales consideran que la superposici??n del gato "vivo y muerto" es bastante real. Intentado como una cr??tica de la interpretaci??n de Copenhague (la ortodoxia predominante en 1935), el experimento mental del gato de Schr??dinger sigue siendo una piedra de toque para las interpretaciones modernas de la mec??nica cu??ntica y puede usarse para ilustrar y comparar sus fortalezas y debilidades.
                                        </p>
                                    </section>
                                </div>
                            </v-card>
						</v-col>
					</v-row>
					<v-row>
						<v-col sm="12" lg="12" >
							<v-card
								elevation="4"
								outlined
								class="grey lighten-2"
							>
								<div style="padding: 10px" class="d-flex justify-space-around ">
									<div class="d-flex justify-space-between align-center">
										<img src="../assets/Person.jpg" height="30px">
										Diego David Vallejo
									</div>
									<div class="d-flex justify-space-between align-center">
										<img src="../assets/Phone.png" height="30px"> 
										5878-9299
									</div>
									<div class="d-flex justify-space-between align-center">
										<img src="../assets/Gmail.png" height="25px">
										dvallejo@unis.edu.gt
									</div>
									<div class="d-flex justify-space-between align-center">
										<img src="../assets/Instagram.png" height="30px"> 
										@diego_vj_
									</div>
								</div>
							</v-card>
						</v-col>
					</v-row>
				</v-container>
			</v-main>
		</v-app>
	</div>
</template>