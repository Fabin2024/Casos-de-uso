# clone o repositório
git clone https://github.com/seu-repo.git
cd Neo Call

# restaure pacotes e crie o banco
dotnet restore
dotnet ef database update

# rode o projeto
dotnet run
