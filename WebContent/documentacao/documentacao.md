
# escopo de requisicao
	@RequestScoped
	@ViewScoped           = sobrevive a varios request


# Calendar
	Calendar    = dados do modelo c este tipo d objeto recebem anotaçao	



# h:messages, h:message
	exibir as messagens de erros


# FacesContext
	FacesContext.getCurrentInstance().addMessage("autor",
					new FacesMessage("Livro deve ter pelo menos um Autor."));


# Ajax
	<f:ajax execute="autor" render="tabelaAutores" />


	event="blur"



	@form
	@all
	@this
	@none


# ciclo de vida do jsf


# redirecionamento
	faces-redirect=true


# templates reutilizaveis
	ui:composition


# viewAction jsf2.1
	para uma variavel do tipo GET na url


# classe Autorizador
	completa o pocesso de login