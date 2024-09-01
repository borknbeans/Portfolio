<script>
    import { page } from '$app/stores';
  </script>
  
  <div class="flex flex-grow bg-gray-200">
    <div class="flex w-2/5 max-w-screen-md mx-auto p-4 items-center justify-center">
        <div class="p-4 flex flex-col">
            <h1 class="text-4xl font-bold">{$page.status} {$page.error?.message}</h1>
            <p class="text-lg text-gray-500">Sorry for the inconvenience</p>
        </div>
    </div>
</div>
