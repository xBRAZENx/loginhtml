# loginhtml
<--
<div class="container mt-5">
    <div class="row justify-content-center">
        <div class="col-md-6">
            <h2 class="mb-4">University Login</h2>
            <form>
                <div class="mb-3">
                    <label for="username" class="form-label">Username</label>
                    <input type="text" class="form-control" id="username" required>
                </div>
                <div class="mb-3">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control" id="password" required>
                </div>
                <div class="mb-3">
                    <label for="userType" class="form-label">User Type</label>
                    <select class="form-select" id="userType" required>
                        <option value="">Select User Type</option>
                        <option value="Admin">Admin</option>
                        <option value="Student">Student</option>
                        <option value="Faculty">Faculty</option>
                    </select>
                </div>
                <button type="button" class="btn btn-dark" (click)="Authentication()">Login</button>
            </form>
        </div>
    </div>
</div>
-->
