<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-success">
            <div class="container-fluid">
                <button class="border border-white navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class=" navbar-toggler-icon"></span>
                </button>
                <div>
                    <h1>Logo</h1>
                </div>
                <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
                    <a class="navbar-brand" href="#">Hidden brand</a>
                    <ul class="mb-2 navbar-nav me-auto mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Category 1</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Category 2</a>
                        </li>
                    </ul>
                    <form class="d-flex" role="search">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-outline-success" type="submit">Search</button>
                    </form>
                </div>

            </div>

        </nav>
    </div>
</template>